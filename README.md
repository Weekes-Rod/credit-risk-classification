# Credit Risk Analysis Report

## Overview
This analysis aims to predict the credit risk of loans using a logistic regression model based on various loan attributes.

## Instructions
### Split the Data into Training and Testing Sets
1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
2. Create the labels set (y) from the “loan_status” column and create the features (X) DataFrame from the remaining columns.
3. Split the data into training and testing datasets by using train_test_split.

### Create a Logistic Regression Model with the Original Data
1. Fit a logistic regression model by using the training data (X_train and y_train).
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
3. Generate a confusion matrix.
4. Print the classification report.
5. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

### Write a Credit Risk Analysis Report
1. Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework.
2. Structure your report by using the provided report template, ensuring that it contains an overview of the analysis, the results, and a summary.
3. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

## Results
- **Accuracy**: 0.99
- **Precision**: 0.85
- **Recall**: 0.91

## Summary
The logistic regression model performs well in predicting credit risk. It achieves an accuracy of 0.99, indicating strong overall performance. The precision score of 0.85 for high-risk loans (label 1) suggests that among the loans predicted as high-risk, 85% are actually high-risk. The recall score of 0.91 indicates that the model correctly identifies 91% of the actual high-risk loans. Overall, these metrics demonstrate the model's effectiveness in identifying both healthy and high-risk loans. Based on these results, I recommend using this model for credit risk classification.
