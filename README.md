# KNN
Implementaion of the KNN algorithm for sepal length of flowers taken from the iris dataset. KNN is a supervised learning method used for classification.
The algorithm looks at a data point's k nearest neighbours and assigns them a class label. The key to this algorithm is choosing the right k value,
a lower k may be susceptible to noise, take for example an outlier point. A higher k may over smooth the boundaries leading to misclassifications around
them.

Low k's are more sensitive to noise (high variance)
High k's are less sensitive to noise, risk of overfitting (high bias).
