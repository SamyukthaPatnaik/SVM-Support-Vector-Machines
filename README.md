# SVM (Support Vector Machines)
- Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.
- The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that we can easily put the new data point in the correct category in the future. This best decision boundary is called a hyperplane.
- SVM algorithm can be used for Face detection, image classification, text categorization, etc.

![Picture](https://static.javatpoint.com/tutorial/machine-learning/images/support-vector-machine-algorithm.png)

## Hyperplane and Support Vectors
**Hyperplane:** There can be multiple lines/decision boundaries to segregate the classes in n-dimensional space, but we need to find out the best decision boundary that helps to classify the data points. This best boundary is known as the hyperplane of SVM.

**Support Vectors:** The data points or vectors that are the closest to the hyperplane and which affect the position of the hyperplane are termed as Support Vector. Since these vectors support the hyperplane, hence called a Support vector.

## Types of SVM
SVM can be of two types:

**1. Linear SVM:** Linear SVM is used for linearly separable data, which means if a dataset can be classified into two classes by using a single straight line, then such data is termed as linearly separable data, and classifier is used called as Linear SVM classifier.

Suppose we have a dataset that has two tags (green and blue), and the dataset has two features x1 and x2

We want a classifier that can classify the pair(x1, x2) of coordinates in either green or blue. Consider the below image:

![Image](https://static.javatpoint.com/tutorial/machine-learning/images/support-vector-machine-algorithm3.png)

So as it is 2-d space so by just using a straight line, we can easily separate these two classes. But there can be multiple lines that can separate these classes. Consider the below image:

![Image](https://static.javatpoint.com/tutorial/machine-learning/images/support-vector-machine-algorithm4.png)

![Image](https://static.javatpoint.com/tutorial/machine-learning/images/support-vector-machine-algorithm5.png)

Hence, the SVM algorithm helps to find the best line or decision boundary; this best boundary or region is called as a hyperplane. 

SVM algorithm finds the closest point of the lines from both the classes. These points are called support vectors. 

The distance between the vectors and the hyperplane is called as margin. And the goal of SVM is to maximize this margin. 

The hyperplane with maximum margin is called the optimal hyperplane.

**2. Non-linear SVM:** Non-Linear SVM is used for non-linearly separated data, which means if a dataset cannot be classified by using a straight line, then such data is termed as non-linear data and classifier used is called as Non-linear SVM classifier.

 
