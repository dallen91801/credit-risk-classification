# Credit Risk Analysis Report

## **Overview of the Analysis**

The purpose of this analysis is to evaluate the performance of a machine learning model in predicting the risk level of loans. Specifically, we aim to classify loans into two categories:

- `0` – Healthy Loan (Low Risk)
- `1` – High-Risk Loan

By using a logistic regression model, we can assess whether borrowers are likely to default on their loans, which is critical for lenders to make informed lending decisions. The analysis involves fitting a logistic regression model, evaluating its performance using key metrics, and providing a recommendation based on the results.

# **Credit Risk Analysis Report**

## **Overview of the Analysis**

The purpose of this analysis is to evaluate the performance of a machine learning model in predicting the risk level of loans. Specifically, we aim to classify loans into two categories:

- `` – Healthy Loan (Low Risk)
- `` – High-Risk Loan

By using a logistic regression model, we can assess whether borrowers are likely to default on their loans, which is critical for lenders to make informed lending decisions. The analysis involves fitting a logistic regression model, evaluating its performance using key metrics, and providing a recommendation based on the results.

---

## **Results**

Below is a summary of the performance metrics from the logistic regression model:

### **Logistic Regression Model**

- **Accuracy:** 99%
- **Precision for **``** (Healthy Loan):** 1.00
- **Precision for **``** (High-Risk Loan):** 0.84
- **Recall for **``** (Healthy Loan):** 0.99
- **Recall for **``** (High-Risk Loan):** 0.99
- **F1-Score for **``** (Healthy Loan):** 1.00
- **F1-Score for **``** (High-Risk Loan):** 0.91

**Key Insights:**

- The model performs exceptionally well in identifying healthy loans, with a perfect precision score.
- It also performs strongly in identifying high-risk loans, but it has some false positives, where loans predicted as high-risk are actually healthy.
- The recall score for high-risk loans is very high, meaning the model is effective at catching most risky loans.

---

## **Summary**

Based on the evaluation, the logistic regression model is highly reliable for predicting both healthy and high-risk loans. However, the model's precision for high-risk loans could be improved to reduce false positives.

### **Recommendation**

Given the high recall score for high-risk loans, the model is recommended for use by lenders to minimize potential financial losses. However, it is important to note that improving precision for high-risk loans would further enhance the model's performance.

### **Suggestions for Further Improvement**

1. **Threshold Tuning:** Adjust the decision threshold to find an optimal balance between precision and recall.
2. **Model Comparison:** Explore other machine learning models such as Random Forest or Gradient Boosting to see if they provide better precision without sacrificing recall.
3. **Feature Engineering:** Investigate additional features that could improve the model's predictions.

---

## **Final Assessment**

The logistic regression model provides a solid foundation for credit risk analysis. It performs exceptionally well in identifying healthy loans and is highly effective at catching high-risk loans. With some additional tuning and exploration of alternative models, the performance could be further enhanced to reduce false positives and improve precision for hig

---

## **Results**

Below is a summary of the performance metrics from the logistic regression model:

### **Logistic Regression Model**

- **Accuracy:** 99%
- **Precision for ********`0`******** (Healthy Loan):** 1.00
- **Precision for ********`1`******** (High-Risk Loan):** 0.84
- **Recall for ********`0`******** (Healthy Loan):** 0.99
- **Recall for ********`1`******** (High-Risk Loan):** 0.99
- **F1-Score for ********`0`******** (Healthy Loan):** 1.00
- **F1-Score for ********`1`******** (High-Risk Loan):** 0.91

**Key Insights:**

- The model performs exceptionally well in identifying healthy loans, with a perfect precision score.
- It also performs strongly in identifying high-risk loans, but it has some false positives, where loans predicted as high-risk are actually healthy.
- The recall score for high-risk loans is very high, meaning the model is effective at catching most risky loans.

---

## **Summary**

Based on the evaluation, the logistic regression model is highly reliable for predicting both healthy and high-risk loans. However, the model's precision for high-risk loans could be improved to reduce false positives.

### **Recommendation**

Given the high recall score for high-risk loans, the model is recommended for use by lenders to minimize potential financial losses. However, it is important to note that improving precision for high-risk loans would further enhance the model's performance.

### **Suggestions for Further Improvement**

1. **Threshold Tuning:** Adjust the decision threshold to find an optimal balance between precision and recall.
2. **Model Comparison:** Explore other machine learning models such as Random Forest or Gradient Boosting to see if they provide better precision without sacrificing recall.
3. **Feature Engineering:** Investigate additional features that could improve the model's predictions.

---

## **Final Assessment**

The logistic regression model provides a solid foundation for credit risk analysis. It performs exceptionally well in identifying healthy loans and is highly effective at catching high-risk loans. With some additional tuning and exploration of alternative models, the performance could be further enhanced to reduce false positives and improve precision for high-risk loans.

