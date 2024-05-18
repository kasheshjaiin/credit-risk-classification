# Credit Risk Analysis Report

## Overview of the Analysis
This analysis aims to develop machine learning models to predict credit risk for loans using historical
lending data from a peer-to-peer lending services company. The dataset contains various financial attributes
such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.
The target variable loan_status indicates whether a loan is healthy (0) or high-risk (1). The purpose is to build models that can accurately classify loans based on these attributes.

## Results

* Logistic Regression Model:
    - Accuracy Score: 0.99
    - Precision Score (Healthy Loan - Label 0): 1.00
    - Precision Score (High-Risk Loan - Label 1): 0.85
    - Recall Score (Healthy Loan - Label 0): 0.99
    - Recall Score (High-Risk Loan - Label 1): 0.91

## Summary

The logistic regression model demonstrates promising performance in predicting credit risk. With high accuracy, precision, and recall scores for both healthy and high-risk loans, it appears to be the best-performing model for this task. The balanced performance across precision and recall metrics suggests that the model effectively identifies both healthy and high-risk loans.

In terms of problem-solving, the performance of the model is crucial for minimizing the risk of default and optimizing loan portfolio management. While predicting healthy loans (`0` label) is important for maintaining a low-risk portfolio, accurately identifying high-risk loans (`1` label) is equally critical for risk mitigation.

Based on the robust performance observed in the logistic regression model, I recommend deploying it for credit risk prediction. Its accuracy and balanced precision and recall scores make it a reliable tool for identifying both healthy and high-risk loans, enabling the company to make informed lending decisions and minimize the risk of default.

