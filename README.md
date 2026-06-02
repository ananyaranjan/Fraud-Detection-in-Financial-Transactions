# Fraud-Detection-in-Financial-Transactions
Machine learning project for detecting fraudulent financial transactions on an imbalanced dataset.

## Overview
This project focuses on detecting fraudulent financial transactions using machine learning techniques. Due to the highly imbalanced nature of fraud datasets, multiple imbalance handling methods were explored and compared to improve fraud detection performance.

## Dataset
The dataset contains financial transaction records with features such as transaction amount, transaction type, account balances before and after transactions, and fraud labels.

## Models Used
Logistic Regression
Random Forest
XGBoost

## Imbalance Handling Techniques
Baseline (No Resampling)
SMOTE (Synthetic Minority Oversampling Technique)
SMOTE-Tomek
Class Weighting

## Evaluation Metrics
The models were evaluated using:

Accuracy
Precision
Recall
F1-Score
ROC-AUC

## Results
XGBoost achieved the strongest overall performance among all models tested. The baseline XGBoost model provided the best balance between precision and recall, while SMOTE-based XGBoost models achieved the highest recall, making them effective for detecting fraudulent transactions.
