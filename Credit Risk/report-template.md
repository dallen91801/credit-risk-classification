# Module 12 Report Template

## Overview of the Analysis

Module 12 Report Template

Overview of the Analysis

This analysis aimed to develop a machine learning model to predict loan risk based on financial data. The goal was to determine whether a loan is classified as high-risk (1) or healthy (0) to assist lenders in making informed decisions and minimizing financial losses.

The dataset contained financial indicators such as:

Loan size

Interest rate

Borrower’s income

Debt-to-income ratio

Number of accounts

Derogatory marks (adverse financial events)

Total debt

Loan status (Target Variable: 0 = Healthy Loan, 1 = High-Risk Loan)

A key observation in the dataset was the imbalance in loan status values:

Healthy Loans (0): 75,036

High-Risk Loans (1): 2,500
This imbalance presented a challenge, as the model could be biased toward predicting loans as healthy due to their higher frequency in the dataset. I applied a class balance healthy loan to address this, including adjusting class weight to address this, ts in the logistic regression model.

The machine learning process included the following steps:

Data Preparation – The dataset was loaded, and the target variable (loan_status) was separated from the features (X).

Train-Test Split – The data was divided into 80% training and 20% testing to evaluate the model’s performance on unseen data.: To evaluate the model's performance on unseen data, the

Model Selection – Logistic Regression was chosen due to its effectiveness in binary classification problems. Alternative models, such as Random Forest and Gradient Boosting, were also considered but were not tested in this analysis.:because it is effective

Class Imbalance Handling – Class weights were adjusted in the logistic regression model to improve recall for high-risk loans.

Model Evaluation – The model’s accuracy, precision, and recall scores were analyzed to assess its effectiveness in identifying high-risk loans.: Theof the model 

#Results

#Machine Learning Model 1: Logistic Regression

Accuracy: 99% (The model correctly classified 99 out of 100 loans.)

Confusion Matrix:

[[14918   83]
 [    9  498]]

Precision & Recall Scores:

Healthy Loans (0):

Precision: 1.00 (The model never falsely classified a loan as risky when it was safe.)

Recall: 0.99 (99% of all truly safe loans were correctly identified.)

High-Risk Loans (1):

Precision: 0.86 (When the model predicted a risky loan, it was correct 86% of the time.)

Recall: 0.98 (98% of hazardous loans were successfully flagged.)

##Summary

#Which one seems to perform best? How do you know it performs best?

The Logistic Regression model was the best-performing model, achieving 99% accuracy and a 98% recall for high-risk loans. This means it correctly identified nearly all risky borrowers, which is essential for lenders to avoid financial losses. Additionally, the model used class weighting to balance the dataset, which helped improve its ability to detect high-risk loans.

#Does performance depend on the problem we are trying to solve?

Yes, performance depends on what we are trying to achieve. In loan risk prediction, identifying high-risk loans (1’s) is more important than identifying safe ones. Lenders need to catch risky borrowers to avoid financial losses. However, this comes with a trade-off—while recall is high (98%), precision is lower (86%), meaning some safe borrowers might be mistakenly labeled risky.

#Please justify your reasoning if you do not recommend any models.

I recommend using Logistic Regression with class weight adjustments because it balances accuracy and recall, making it a reliable tool for lenders. However, to make the model even better, we could test other models like Random Forest or Gradient Boosting, which might improve precision while still maintaining a high recall. These models could help reduce false positives, ensuring that good borrowers are not mistakenly flagged as high-risk while still catching actual risky loans.

REFERENCES:

https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html

https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html

CHATGPT
