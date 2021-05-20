# Credit_Risk_Analysis

## Overview 
This analysis will show and compare several different tests such as oversampling, undersampling, a combination of ensemble techniques, and logistical regression to determine which machine learning models performed the best at determining credit risk. 

__Tools__:

Pandas, Python, Jupyter Notebooks
# Results

## Random Oversampling and Logistic Regression
- Accuracy Score: 0.647
- Precision: 0.99
- Recall: 0.60
- F1: 0.75

![](Resources/Random_OverSampling.PNG)

## SMOTE Oversampling
- Accuracy Score: 0.662
- Precision: 0.99
- Recall: 0.69
- F1: 0.81

![](Resources/Smote_OverSampling.PNG)

## Undersampling
- Accuracy Score: 0.544
- Precision: 0.99
- Recall: 0.69
- F1: 0.56

![](Resources/UnderSampling.PNG)

## Combination (Over and under) Sampling 
- Accuracy Score: 0.649
- Precision: 0.99
- Recall: 0.60
- F1: 0.81

![](Resources/Combination_Sampling.PNG)

## Balanced Random Forest
- Accuracy Score: 0.782
- Precision: 0.99
- Recall: 0.70
- F1: 0.93

![](Resources/Balanced_Random_Forest.PNG)

## Easy Ensemble AdaBoost Classifier
- Accuracy Score: 0.917
- Precision: 0.99
- Recall: 0.89
- F1: 0.96

![](Resources/Easy_Ensemble_AdaBoost.PNG)

# Summary
I would feel confident in recommending the Easy Ensemble AdaBoost Classifier as the best model to use out of these six. The model is far ahead of the competition in its accuracy score and F1 score. Having scores in the 90 percentile is an acceptable industry standard. 

