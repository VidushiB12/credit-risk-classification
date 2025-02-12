# credit-risk-classification

Purpose of the Analysis 

The goal of this analysis is to predict loan risk by using a logistic regression model and evaluating its performance in predicting the loan risk. The loans can be classified into two categories:

Class 0 (Healthy Loan): Loans that are low-risk.
Class 1 (High-Risk Loan): Loans that have a higher likelihood of default.

By using the model's performance metrics, we can determine whether it is suitable for helping a company to make informed decisions about giving loans to its customers.

Model Performance Metrics
Accuracy: 99% – The model correctly classifies the majority of loans.
Precision:
Class 0: 1.00 – Almost all predicted healthy loans are truly healthy.
Class 1: 0.84 – 84% of predicted high-risk loans are actually high-risk.
Recall:
Class 0: 0.99 – The model correctly identifies 99% of actual healthy loans.
Class 1: 0.94 – The model captures 94% of actual high-risk loans.

Summary

The model demonstrates excellent overall performance, particularly in predicting healthy loans (Class 0) with near-perfect precision and recall. However, it has slightly lower precision for high-risk loans (Class 1), meaning some low-risk loans might be mistakenly classified as high-risk. This model can be recommended to companies if adjustments are made to make informed decisions about high-risk loan. Some recommendations are: adjusting the decision threshold to balance precision and recall for Class 1. With the enhancements, the model can be a valuable tool for reducing financial risk and improving loan approval decisions.