# Credit_Risk_Analysis

## Overview 
The purpose of this analysis is to employ different techniques to train and evaluate models with unbalanced classes using a credit card dataset.Using various libraries and algorithms were able to build and evaluate models using resampling including:
- imbalanced-learn
- scikit-learn
- RandomOverSampler
- SMOTE algorithms
- ClusterCentroids algorithm
- SMOTEENN algorithm
- BalancedRandomForestClassifier (bias reduction model)
- EasyEnsembleClassifier (bias reduction model)

## Results 
Naive Random Oversampling
<img width="775" alt="Screenshot 2023-04-25 at 11 46 08 AM" src="https://user-images.githubusercontent.com/120140614/234332184-ca2a0c26-98dc-4935-bbbf-5260767b4eb1.png">
The balanced accuracy for the naive random oversampling is 64%. The imbalanced classification report shows that precision is low for the high risk and low for the low risk. The recall score .59/.69.

SMOTE Oversampling 

<img width="818" alt="Screenshot 2023-04-25 at 11 51 09 AM" src="https://user-images.githubusercontent.com/120140614/234333092-80ea9239-691d-4719-8a11-06caf1e7e672.png">

The balanced accuracy for the SMOTE oversamping is 63.6%. The imbalanced classification report shows that precision is low for the high risk and low for the low risk. The recall is .63/.64

Undersampling 
<img width="787" alt="Screenshot 2023-04-25 at 11 53 25 AM" src="https://user-images.githubusercontent.com/120140614/234333689-7394f88d-8f66-4c3a-9a57-8b4b9aed554c.png">

Combination Sampling 
<img width="736" alt="Screenshot 2023-04-25 at 11 54 08 AM" src="https://user-images.githubusercontent.com/120140614/234333883-d1051dc3-077e-40ba-b04c-5d7c56a0e160.png">

Balanced Random Forest Classifier 
<img width="748" alt="Screenshot 2023-04-25 at 11 55 15 AM" src="https://user-images.githubusercontent.com/120140614/234334205-33b7af9e-29c1-4d55-bf9c-c9d0ffc73522.png">

Easy Ensemble Adaboost Classifier 
<img width="782" alt="Screenshot 2023-04-25 at 11 56 04 AM" src="https://user-images.githubusercontent.com/120140614/234334412-ea1835bf-defc-42cd-b613-0b66ce102d9d.png">


## Summary 



