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

<img width="462" alt="Screen Shot 2022-09-01 at 6 29 17 PM" src="https://user-images.githubusercontent.com/104380112/188025572-835013a7-bceb-49af-8ebf-aa2a747583bd.png">

**SMOTE Oversampling**
- Accuracy score = 0.64
- This model has a 64% of accuracy at predicting credit risks
- It achieved an average F-score of only 0.78 and an F-score for high-risk prediction of only 0.02.

<img width="463" alt="Screen Shot 2022-09-01 at 6 29 23 PM" src="https://user-images.githubusercontent.com/104380112/188025583-86e8779a-4fed-409a-8ee6-caf4aea429aa.png">

**Undersampling**
- Accuracy score = 0.45
- This model had the lowest performance with only 45% of accuracy at predicting credit risks.
- It achieved an average F-score of only 0.62 and an F-score for high-risk prediction of only 0.01.

<img width="452" alt="Screen Shot 2022-09-01 at 6 29 30 PM" src="https://user-images.githubusercontent.com/104380112/188025595-4961acf2-e13a-4044-8910-f0756b0432e3.png">

**Combination Over and Under Sampling**
- Accuracy score = 0.54
- This model had the second-lowest performance with only 54% of accuracy at predicting credit risks
- It achieved an average F-score of 0.70 and an F-score for high-risk prediction of only 0.02.

<img width="466" alt="Screen Shot 2022-09-01 at 6 29 37 PM" src="https://user-images.githubusercontent.com/104380112/188025618-f919cc5a-65dc-4760-a6a7-c5230d03295c.png">

**Balanced Random Forest Classifier**
- Accuracy score = 0.91
- This was the second best-performing model with a 91% of accuracy at predicting credit risks.
- It achieved an average F-score of 0.95, however its F-score for high-risk prediction was still low at only 0.07.

<img width="452" alt="Screen Shot 2022-09-01 at 6 29 45 PM" src="https://user-images.githubusercontent.com/104380112/188025636-19e21e10-3035-42f2-a7b4-904f792aac82.png">

**Easy Ensemble Classifier**
- Accuracy score = 0.94
- This was the best-performing model with a 94% of accuracy at predicting credit risks.
- It achieved an average F-score of 0.97, however its F-score for high-risk prediction was still low at only 0.14.

<img width="452" alt="Screen Shot 2022-09-01 at 6 29 51 PM" src="https://user-images.githubusercontent.com/104380112/188025646-3e9de896-e6aa-4578-aaa3-c740b8c8b858.png">

## Summary 
Overall the best performing models were the Easy Ensemble Classifier and the Balanced Random Forest Classifier with an acuraccy score higher than 90%. However, I would advise not to use any of these algorithms given the low F-score for high-risk prediction, which was between 0.07 to 0.14. Creditors would still face a high risk of approving credit cards to high risk clients. 
