# Machine Learning


Machine Learning is the science of programming computers so they can learn from data.

Machine learning algorithms are used in the applications of email filtering, detection of network intruders, and computer vision, where it is infeasible to develop an algorithm of specific instructions for performing the task. _( Source : wikipedia )_


## Supervised and Unsupervised Machine Learning Algorithms

__Supervised Learning__ : data is labeled and the program learns to predict the output from the input data.

__Unsupervised Learning__ : data is unlabeled and the program learns to recognize the inherent structure in the input data

<p align="center">
  <img width="480" height="360" src="images\Machine_Learning.png">
</p>


## Regression vs Classification

Supervised learning problems can be further grouped into regression and classification problems.

  - __Regression__ : A regression problem is when the output variable is a real value, such as “dollars” or “weight”.

For example:

  - Predict the height of a potted plant from the amount of rainfall.
  - Predict salary based on someone's age and availability of high-speed internet.
  - Predict a car's MPG (miles per gallon) based on size and model year.

  - __Classification__ : A classification problem is when the output variable is a category, such as “red” or “blue” or “disease” and “no disease”.

 Multi-label classification is when there are multiple possible outcomes. It is useful for customer segmentation, image categorization, and sentiment analysis for understanding text. To perform these classifications, we use models like Naive Bayes, K-Nearest Neighbors, and SVMs.

For example:

  - Predict whether an email is spam or not.
  - Predict whether it will rain or not.
  - Predict whether a user is a power user or a casual user.


Some popular examples of supervised machine learning algorithms are:

  - Linear regression for regression problems.
  - Random forest for classification and regression problems.
  - Support vector machines for classification problems.

## Clustering vs Association

Unsupervised learning problems can be further grouped into clustering and association problems.

  - __Clustering__ : A clustering problem is where you want to discover the inherent groupings in the data, such as grouping customers by purchasing behavior.

  - __Association__ :  An association rule learning problem is where you want to discover rules that describe large portions of your data, such as people that buy X also tend to buy Y.

Some popular examples of unsupervised learning algorithms are:

  - k-means for clustering problems.
  - Apriori algorithm for association rule learning problems.


## Normalization

Normalizing your data is an essential part of machine learning. You might have an amazing dataset with many great features, but if you forget to normalize, one of those features might completely dominate the others. It's like you're throwing away almost all of your information! Normalizing solves this problem.

Techniques to normalize:

  - __Min-max normalization__: Guarantees all features will have the exact same scale but does not handle outliers well.

  - __Z-score normalization__: Handles outliers, but does not produce normalized data with the exact same scale.

## Steps Involved in Machine Learning Project

A machine learning project involves the following steps:

  - Gathering Data
  - Data preparation
  - Choosing a model
  - Training the model
  - Evaluate the model
  - Tune the model
  - Make Predictions
