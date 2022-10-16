# Credit_Risk_Analysis

## Overview of the project

In this project will be using machine learning to evaluate credit card risk by employing different techniques to train and evaluate models.

### Resources

#### Software

• Python

• Conda

• Jupyter Notebook

• Terminal

#### Data Source

• LoanStats_2019Q1.csv

## Results

### Use Resampling Models to Predict Credit Risk

#### Naive_Random_Oversampling

Accuracy Score: 63.8%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 61%
Recall Low Risk: 66%

<img width="761" alt="Native_Random_OverSampling" src="https://user-images.githubusercontent.com/107282754/196039807-2b68a3dd-14e7-4841-96d5-fe0f6faab9f8.png">

#### SMOTE_Oversampling

Accuracy Score: 65.89%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 62%
Recall Low Risk: 69%

<img width="720" alt="SMOTE_Oversampling" src="https://user-images.githubusercontent.com/107282754/196039931-89df9852-920b-40c3-acae-6e5cd8393a88.png">

#### Cluster_Centroid_Undersampling

Accuracy Score: 65.89%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 69%
Recall Low Risk: 40%

<img width="733" alt="UnderSampling" src="https://user-images.githubusercontent.com/107282754/196040096-4dfbedf9-075c-4b87-9f30-3f923f664005.png">

### Use SMOTEENN Algorithm to Predict Credit Risk

#### Combination Over/Under Sampling

Accuracy Score: 64.82%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 72%
Recall Low Risk: 57%

<img width="745" alt="Combination _Over_Under_Sampling" src="https://user-images.githubusercontent.com/107282754/196040177-733da059-a165-4331-8658-45d87425833f.png">

### Use Ensemble Classifiers to Predict Credit Risk


#### Balanced Random Forest Classifier

<img width="751" alt="Balance_Random_Forest_Classifier" src="https://user-images.githubusercontent.com/107282754/196040297-53d003c7-c5de-4612-9960-17f55b3b43d1.png">

Accuracy Score: 75.21%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 63%
Recall Low Risk: 87%

#### Easy Ensemble AdaBoost Classifier

<img width="753" alt="Easy_Ensemble_AdaBoost_Classifier" src="https://user-images.githubusercontent.com/107282754/196040370-546ac23d-df2e-4cc5-b39a-c9abf2ac5493.png">

Accuracy Score: 93.16%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 92%
Recall Low Risk: 94%

## Summary
