# credit-risk-classification
Within the "Credit_Risk" folder, open the "credit_risk_classification" file in Jupyter Notebook. Run all of the cells for output of results of the model. The "lending_data" CSV is in the "Resoruces" folder. The path to the CSV is located in the Jupyter Notebook code.

ChatGPT was used to debug code.

Credit Risk Analysis Report

Overview:

In the analysis for this challenge, I built a logistic regression model to predict the risk of loan borrowers. A varitey of factors were used including the requested loan size and interest rate, income, debt to income ratio, number of accounts, derogatory marks and total debt. I ultimately aimed to preidct if the loan was healthy (0) or high risk (1). 

Results:

Accuracy: 0.99
Precision for Healthy Loan (0): 1.00
Recall for Healthy Loan (0): 0.99
Precision for High-Risk Loan (1): 0.84
Recall for High-Risk Loan (1): 0.94
F1-Score for Healthy Loan (0): 1.00
F1-Score for High-Risk Loan (1): 0.89
Macro Average F1-Score: 0.94
Weighted Average F1-Score: 0.99

Summary:

Overall, the performance of this model was excellent, with an accuracy of 99%. The model was better at predicting healthy loans with a precision of 1. The high risk loans had a precision of .84. I would recommend the logistic regression model for classifying loan risk. However, there is room for improvement for classifying the high risk loans.
