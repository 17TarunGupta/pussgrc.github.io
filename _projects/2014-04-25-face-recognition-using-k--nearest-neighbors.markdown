---
layout: project
title:  "Face Recognition"
date:   2017-08-15 16:54:46
author: Rahul Kumar
categories:
- project
img: portfolio_01.jpg
carousel:
- single01.jpg
- single02.jpg
- single03.jpg
tagged: Machine Learning
website: https://www.linkedin.com/in/rahul10-pu
---
Face Recognition using K-Nearest Neighbors

**Packages to Install:-**

* Python 2.7
* Numpy, SciPy
* Mathplotlib
* OpenCV Python

**KNN classifier** 

>is best suited for classifying persons based on their images due to its lesser execution time and better accuracy than other commonly used methods which include Hidden Markov Model and Kernel method. Although methods like SVM and Adaboost algorithms are proved to be more accurate than KNN classifier, KNN classifier has a faster execution time and is dominant than SVM.

>The simplest classification scheme is a nearest neighbor classification in the image space. Under this scheme an image in the test set is recognized by assigning to it the label of the closest point in the learning set, where distance are measured in image space.

>The Euclidean distance metric is often chosen to determine the closeness between the data points in KNN. A distance is assigned between all pixels in a dataset. Distance is defined as the Euclidean distance between two pixels. This Euclidean distance is by default in a KNN classifier. But the distance between two features can be measured based on one of the distance cosine and correlation.

**K-NN Algorithm**
>The k-nearest neighbour algorithm (k-NN) is a method for classifying objects based on closest training examples in the feature space. K-NN is a type of instance-based learning, or lazy learning where the function is only approximated locally and all computation is deferred until classification.
The k-nearest neighbour algorithm is amongst the simplest of all machine learning algorithms: an object is classified by a majority vote of its neighbours, with the object being assigned to the class most common amongst its k nearest neighbours (k is a positive integer, typically small). 

>If k = 1, then the object is simply assigned to the class of its nearest neighbour. 

> --1. Each data pixel value within the data set has a class label in the set, Class = {c1,...,cn}.
 
> --2. The data points', k-closest neighbors (k being the  number of neighbors) are then found by analyzing the distance matrix.
 
>  --3. The k-closest data points are then analyzed to determine which class label is the most common among the set.
  
>  --4. The most common class label is then assigned to the data point being analyzed. 
