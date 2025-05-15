# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to build and evaluate a supervised machine learning model to predict the credit risk of loans.  Specifically, we used logistic regression to predict whether a loan is "healthy" (low risk) or "high risk" (likely to default) based on different loan characteristics such as loan size, borrowers income, debt to income ratio, and other financial indicators.

## Results

* Accuracy: 99%
* Precision: (Healthy Loans - 0): 1.00
* Recall (Healthy Loans - 0): 0.99
* Precision (High Risk Loans - 1): 0.84
* Recall (High Risk Loans - 1): 0.94

## Summary

The logistic regression model performs exceptionally well at predicting healthy loans (1.0) and fairly well at detecting high-risk loans (0.84). The model’s high overall accuracy (99%) and strong recall for high-risk loans suggest it is effective at identifying most potential defaults, which is critical for financial risk management. Given its performance and interpretability, I recommend this model for use by the company as a strong starting point for assessing borrower risk. However, given the slightly lower precision for high risk loans (0.84), some additional model tuning (or more data) could further enhance its reliability before deploying it in a high stakes environment.



