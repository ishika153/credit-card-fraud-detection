# Credit Card Fraud Detection using XGBoost

## Overview
Credit card fraud detection using **XGBoost** on a highly imbalanced
transaction dataset.

## Dataset
Credit Card Fraud Detection dataset from Kaggle.
Dataset: `mlg-ulb/creditcardfraud`  
File: `creditcard.csv`

[Dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
`creditcard.csv` is not included because of its large file size.

## Techniques Used
- Data Cleaning
- Train-Test Split
- SMOTE for class imbalance
- XGBoost Classifier
- Precision, Recall, F1 Score and ROC-AUC
- Decision Threshold Tuning
- Feature Importance

## Results

Best tested threshold: **0.9**

- Precision: **0.9706**
- Recall: **0.9429**
- F1 Score: **0.9565**

### Top Feature
**V14 — 0.679804**

## Files
- `Credit_Card_Fraud_Detection_XGBoost.ipynb` — Complete project notebook
- `README.md` — Project description

Precision: 0.9706
Recall: 0.9429
F1 Score: 0.9565

## Feature Importance
The most important feature for the trained XGBoost model was V14.
