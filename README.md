# Logistic_regression
LOGISTIC REGRESSION

Logistic regression is a statistical model used to predict the probability of an outcome. Logistic regression is used when the target variable is categorical in nature. It is a classification algorithm, mainly used for binary classification problems. The objective of a logistic regression is to determine the relationships between features and probability of an outcome.It is named as ‘Logistic Regression’, because it’s underlying technique is quite the same as Linear Regression. The term “Logistic” is taken from the Logit function that is used in this method of classification.

	Assumptions:
a)	There is minimal or no multicollinearity among the independent variables.
b)	Linear relationship between logit of the outcome and the independent variables.  The logit function is described as logit(p) = log(p/(1-p)), where p is the probability of the target outcome.
c)	Logistic regression requires quite large sample sizes to predict properly.
3.	Advantages: 
a)	Very easy to understand, implement, interpret and train.
b)	Requires less training.
c)	Performs well for simple dataset as well as dataset which is linearly separable.
d)	Does not make any assumptions regarding the distributions of classes in feature space.
e)	 A Logistic Regression model is less likely to be over-fitted but it can overfit in high dimensional datasets. To avoid over-fitting these scenarios, One may consider regularization.

	Disadvantages
a)	Lots of feature training is required at times.
b)	Correlation between independent feature may affect the performance of the classifier.
c)	It is better to avoid using logistic regression when the number of features is less than the number of observations. Otherwise, it will lead to overfitting.
d)	It is quite sensitive to noise and overfitting.
e)	Non-linear problems can’t be solved with logistic regression because it has a linear decision surface. Linearly separable data is rarely found in real-world scenarios.
f)	It is not required to obtain complex relationship using logistic regression. In such cases Some algorithms such as neural networks, which are more powerful, and compact can easily outperform Logistic Regression algorithms.
g)	Feature scaling is required.


