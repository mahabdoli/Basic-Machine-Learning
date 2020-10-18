# Basic-Machine-Learning
Python implementation of machine learning algorithms mostly from scratch for Machine learning course at Electrical Engineering Department of Amirkabir University (Tehran Polytechnic). The following algorithms are posted here:
1. Support Vector Machine
2. Bayesian Classifiers
3. K-means Clustering
Other algorithms will be added in the future.

## Support Vector Machine  
The SVM with circularly distributed data [notebook](https://github.com/mahabdoli/Basic-Machine-Learning/blob/master/SVM/SVM%20with%20circular%20distributed%20data.ipynb) demonstrates the effects of using different kernels in the classification output. In this notebook, I have used polar coordinates to generate circularly distributed training and test set data. The decision boundary, margins, and support vectors are visualized after training. Since the generated dataset is not linearly separable, the linear SVM cannot classify the samples effectively.
The Support Vector Machine [notebook](https://github.com/mahabdoli/Basic-Machine-Learning/blob/master/SVM/Support%20Vector%20Machine%20.ipynb), Applies SVM on the Mushrooms dataset available on the UCI Machine Learning Repository. Hyper-parameter C and the kernels are optimized using Scikit-learn’s grid search.

## K-means Clustering
In this [notebook](https://github.com/mahabdoli/Basic-Machine-Learning/blob/master/K-means%20Clustering/Kmeans%20Clustering.ipynb), The K-means algorithm from scratch is implemented on a data set with known number of clusters. Experiments have been conducted to show the sensitivity of K-means to the initial random cluster centroids. Also, Farthest first initialization method has been compared to the random initialization. 

## Bayesian Classifiers
The Naïve Bayes classifier is [applied](https://github.com/mahabdoli/Basic-Machine-Learning/blob/master/Bayes%20classifiers/Naive%20Bayes.ipynb) on the iris data set from the UCI Machine Learning Repository. The Naïve Bayes classifier is not an ideal method to deal with data sets that have non-categorical feature values as it increases the probability of facing the zero-frequency problem. 
The zero frequency problem in Naïve Bayes classifier happens when no occurrence of a certain class label and attribute values are present in the data set. Therefore, the probability estimate will be zero. To solve this problem, the Naïve Bayes implementation with smoothing is applied on the iris data set in this [notebook](https://github.com/mahabdoli/Basic-Machine-Learning/blob/master/Bayes%20classifiers/Naive%20Bayes%20With%20Smoothing.ipynb). As a result the accuracy of the classifer increases significantly (from 53% to 73%). 
