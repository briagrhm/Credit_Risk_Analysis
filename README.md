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

The balanced accuracy for the naive random oversampling is 64%. The imbalanced classification report shows that precision is low with a sensitvity of 59% for the high risk so it is not reliable positive classification and high for the low risk with a senstivity of 69%. The recall score .59/.69 for high to low risk. 

SMOTE Oversampling 

<img width="818" alt="Screenshot 2023-04-25 at 11 51 09 AM" src="https://user-images.githubusercontent.com/120140614/234333092-80ea9239-691d-4719-8a11-06caf1e7e672.png">

The balanced accuracy for the SMOTE oversamping is 63.6% pretty similar to the random sampling.  The imbalanced classification report shows that precision is also low with a sensitivity of 63% for the high risk and high for the low risk that has a sensitivity of 64%. The recall is .63/.64. 

Undersampling 
<img width="787" alt="Screenshot 2023-04-25 at 11 53 25 AM" src="https://user-images.githubusercontent.com/120140614/234333689-7394f88d-8f66-4c3a-9a57-8b4b9aed554c.png">

The balance accuracy for the undersampling is 63.6% as seen in the SMOTE sampling. The imbalanced classifications are similar as before with low precision for the high risk with a sensitivity at 61% and high precision for the low risk with a sensitivity at 45%. The recall is .61/.45 dfor high to low risk. 

Combination Sampling 
<img width="736" alt="Screenshot 2023-04-25 at 11 54 08 AM" src="https://user-images.githubusercontent.com/120140614/234333883-d1051dc3-077e-40ba-b04c-5d7c56a0e160.png">

The balance accuracy for the combinaton sampling is 52.9% which is lower than what was previously seen in the samplings. The imbalanced classification report shows that precision consistent with a low precision for the high risk with a sensitivity of 70%. The high precision for the low risk has a sensitivity of 57%. The recall is .70/.57 this is an improvement from the previous high risk recalls. 

Balanced Random Forest Classifier 
<img width="748" alt="Screenshot 2023-04-25 at 11 55 15 AM" src="https://user-images.githubusercontent.com/120140614/234334205-33b7af9e-29c1-4d55-bf9c-c9d0ffc73522.png">

The balance accuracy for the Balanced Random Forest Classifier is 78.7%. The imbalanced classifications are as seen before for precision but the sensitivities have changed high risk has a sensitivity of 67% and the low risk has a sentsitivity of 91%. This is an improvement in sensitivity for the low risk. 

Easy Ensemble Adaboost Classifier 
<img width="782" alt="Screenshot 2023-04-25 at 11 56 04 AM" src="https://user-images.githubusercontent.com/120140614/234334412-ea1835bf-defc-42cd-b613-0b66ce102d9d.png">
The balance accuracy for the Easy Ensemble Adaboost Classifier is 92.5%. The precisions are the same as the above sampling however the sensitivties have improved with the high risk being at 91% sensitivity and the low risk being at 94% sensitivty. 

## Summary 
The results of all the models used to perform the credit risk analysis show weak precision in determining if a credit risk is high. The Easy Ensemble models brought a lot more improvement specially on the sensitivity of the high risk credits. From the random sampling where it started off at 59% to Ensenmble sampling where it eneded up at 91% this showed about 30% increase in sensitivity. However, because of the low precision for the high risk credis this indicates that low risk credit are being flagged as high risk falsely. This hurts the banks and causes them to miss out on the potential revenue stream. So none of these models seem to be a reliable source for accessing low and high risk credit. 




