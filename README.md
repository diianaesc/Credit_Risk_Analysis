# Credit_Risk_Analysis

## Overview

The purpose of this project is to apply machine learning to solve a real-world challenge: credit card risk. 

Different techniques will be employed to train and evaluate models with unbalanced classes: 

- Oversample using the RandomOverSampler and SMOTE algorithms
- Undersample using the ClusterCentroids algorithm
- Combinatorial approach of over- and undersampling using the SMOTEENN algorithm
- Two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier

We will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk

## Results 

**Naive Random Oversampling**
- Accuracy score = 0.68
- This model has a 68% of accuracy at predicting credit risks
- It achieved an average F-score of only 0.80 and an F-score for high-risk prediction of only 0.02.

**SMOTE Oversampling**
- Accuracy score = 0.64
- This model has a 64% of accuracy at predicting credit risks
- It achieved an average F-score of only 0.78 and an F-score for high-risk prediction of only 0.02.

**Undersampling**
- Accuracy score = 0.45
- This model had the lowest performance with only 45% of accuracy at predicting credit risks.
- It achieved an average F-score of only 0.62 and an F-score for high-risk prediction of only 0.01.

**Combination Over and Under Sampling**
- Accuracy score = 0.54
- This model had the second-lowest performance with only 54% of accuracy at predicting credit risks
- It achieved an average F-score of 0.70 and an F-score for high-risk prediction of only 0.02.

**Balanced Random Forest Classifier**
- Accuracy score = 0.91
- This was the second best-performing model with a 91% of accuracy at predicting credit risks.
- It achieved an average F-score of 0.95, however its F-score for high-risk prediction was still low at only 0.07.
- 
**Easy Ensemble Classifier**
- Accuracy score = 0.94
- This was the best-performing model with a 94% of accuracy at predicting credit risks.
- It achieved an average F-score of 0.97, however its F-score for high-risk prediction was still low at only 0.14.
