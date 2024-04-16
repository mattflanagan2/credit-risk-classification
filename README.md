# credit-risk-classification
## Loan Risk Classification Analysis

### Overview of the Analysis

The purpose of this analysis is to develop and evaluate machine learning models for classifying loan applications into two categories: healthy loans (0) and high-risk loans (1). The dataset contains various features related to loan applications, and the goal is to predict whether a loan is likely to be healthy or high-risk based on these features.

### Results

- **Logistic Regression Model:**
  - Accuracy Score: 0.99
  - Precision Score:
    - Healthy Loans (0): 1.00
    - High-Risk Loans (1): 0.85
  - Recall Score:
    - Healthy Loans (0): 0.99
    - High-Risk Loans (1): 0.91

### Summary

The logistic regression model achieved high accuracy (0.99) and performed exceptionally well in predicting healthy loans, with perfect precision, recall, and F1-score. For high-risk loans, while the precision (0.85) is slightly lower, the model still maintains a high recall (0.91) and F1-score (0.88). Overall, the logistic regression model demonstrates strong performance and is recommended for use by the company as it correctly classified 99% of the loans in the test set.

