# Credit Risk Analysis with Logistic Regression

## Overview

This repository contains an analysis of credit risk using a logistic regression model. The goal of the analysis was to predict the likelihood of loan default, which is crucial for financial institutions to manage and mitigate risk.

### Dataset

The dataset includes financial information on various loans, with features such as:
- **Loan Size**
- **Interest Rate**
- **Borrower Income**
- **Debt-to-Income Ratio**
- **Number of Accounts**
- **Derogatory Marks**
- **Total Debt**

The target variable is `loan_status`, where:
- `0` indicates a healthy loan.
- `1` indicates a high-risk loan.

### Analysis Steps

1. **Data Preparation**: 
   - Loaded the dataset and split it into features (`X`) and target variable (`y`).
   - Further split the data into training and testing sets.

2. **Model Training**:
   - Implemented a logistic regression model using the training data.

3. **Model Evaluation**:
   - Assessed the model’s performance using a confusion matrix and classification report to analyze accuracy, precision, and recall.

## Results

The logistic regression model yielded the following results:

- **Accuracy**: 99%
- **Precision**:
  - **Healthy Loans (0)**: 1.00
  - **High-Risk Loans (1)**: 0.86
- **Recall**:
  - **Healthy Loans (0)**: 0.99
  - **High-Risk Loans (1)**: 0.94

## Summary

The logistic regression model demonstrated strong performance with a 99% accuracy rate. It effectively identifies healthy loans with perfect precision and shows high recall for high-risk loans, making it a reliable tool for predicting loan defaults.

### Recommendation

Given the model's high accuracy and its ability to detect most high-risk loans, it is recommended for use in credit risk assessment by financial institutions. This model can help in making informed lending decisions and managing potential risks.

## Repository Structure

- `lending_data.csv`: The dataset used for analysis.
- `Credit_Risk_Analysis.ipynb`: Jupyter notebook containing the complete analysis.
- `README.md`: This file, providing an overview of the analysis and results.


