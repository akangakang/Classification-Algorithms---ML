# Classification-Algorithms---ML

## Goals
* Implement Two Classification Algorithms
1. Naïve Bayesian
2. Logistic Regression
* Using the sklearn Python package for support vector machines (SVM)
* Compare the performance of several classification methods by conducting an empirical comparative study.

## Dataset

Mobile Price Classification
https://www.kaggle.com/iabhishekofficial/mobile-priceclassification?select=train.csv

## Requirements and Key Points

### Data Splitting
* Split the original ‘train.csv’ into ‘train.csv’, ‘valid.csv’ and ‘test.csv’ with the ratio of 0.8 :0.1 : 0.1, respectively.

### Data Preprocessing
* Convert labels into to two classes: low (0, 1) and high (2, 3)
* For Naïve Bayes, you may need to:
1. discretize continuous attributes into intervals
2. split large number into ranges
* You may need data normalization (i.e., scaling values of attributes tothe same level, e.g., [0, 1])
### Model Implementation
Implement Naïve Bayes and Logistic Regression using Python’s primitive classes and functions. Calling third-party libraries (such as sklearn) for model building (except for SVM) will get 0 points.
