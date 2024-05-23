# Module 12 Report

## Overview of the Analysis
In this analysis, we aimed to develop machine learning models to predict credit risk based on financial information. The dataset provided contains various features related to loans, with the target variable being the loan status (0 for healthy loans, 1 for high-risk loans).

### Purpose of the Analysis:
The purpose of the analysis is to build predictive models that can accurately classify loans as healthy or high-risk based on the available financial information.

### Data Description:
- The dataset includes financial information such as loan amount, interest rate, annual income, debt-to-income ratio, etc.
- The target variable "loan_status" indicates whether a loan is healthy (0) or high-risk (1).
- Basic information about the target variable:
  - Healthy Loans (0): 18765
  - High-Risk Loans (1): 619

### Machine Learning Process:
1. Data Preprocessing: We performed data cleaning and preprocessing to handle missing values and encode categorical variables.
2. Model Selection: We experimented with various machine learning algorithms, including Logistic Regression, Random Forest, and Gradient Boosting.
3. Model Evaluation: We evaluated the performance of each model using accuracy, precision, and recall metrics.

## Results
### Logistic Regression Model:
- **Accuracy Score**: 0.99
- **Precision Score**: 0.85
- **Recall Score**: 0.91


## Summary
- Among the models tested, the Logistic Regression model achieved high accuracy, precision, and recall scores, indicating its effectiveness in predicting credit risk.
- Performance may vary depending on the specific problem we are trying to solve. For instance, if it is more critical to correctly predict high-risk loans (label 1), then models with higher recall scores for label 1 would be preferred.
- Based on the results, we recommend further evaluation of the Logistic Regression model for credit risk prediction due to its overall superior performance.
