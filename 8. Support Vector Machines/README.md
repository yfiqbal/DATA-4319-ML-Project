# Support Vector Machines

![alt text](svm.jfif)

A common task in Machine Learning is to classify data. Given a data point cloud, sometimes linear classification is impossible. In those cases we can use a Support Vector Machine instead, but an SVM can also work with linear separation.

A Support Vector Machine was first introduced in the 1960s and later improvised in the 1990s. It is a supervised learning machine learning classification algorithm that has become extremely popular nowadays owing to its extremely efficient results.

An SVM is implemented in a slightly different way than other machine learning algorithms. It is capable of performing classification, regression and outlier detection.

Support Vector Machine is a discriminative classifier that is formally designed by a separative hyperplane. It is a representation of examples as points in space that are mapped so that the points of different categories are separated by a gap as wide as possible. In addition to this, an SVM can also perform non-linear classification. Let us take a look at how the Support Vector Machine work.

 

Advantages of SVM:  
1. Effective in high dimensional spaces
2. Still effective in cases where the number of dimensions is greater than the number of samples
3. Uses a subset of training points in the decision function that makes it memory efficient
4. Different kernel functions can be specified for the decision function that also makes it versatile

Disadvantages of SVM:  
1. If the number of features is much larger than the number of samples, avoid over-fitting in choosing kernel functions and regularization term is crucial.
2. SVMs do not directly provide probability estimates, these are calculated using five-fold cross-validation.