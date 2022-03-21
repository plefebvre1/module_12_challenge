# Module 12 Report

## Overview of the Analysis

* In this assignment, the goal is to create a model that can identify the creditworthiness of borrowers based on relevant variables
* The variables that are being used to fit the model are financial details about the loan and the borrower including loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt
* The model is trying to predict the status of a loan (healthy - 0, high-risk - 1) based on these variables
* Two datasets were used to train each model - the first model was created using the original data and the second was created using oversampled data
* To create the model, the dataset was split into training and testing datasets. The model is initiated and fitted with the training data. Then predictions are made using the test data.
* The successfulness of the model is assessed by comparing the predicted results to the actual data.

## Results

The first model was done using the original data and the second model was done using oversampled data.

* Machine Learning Model 1:
  * This model was excellent at predicting healthy loans with a precision score of 1.00, recall score of 0.99 and F1 score of 1.00. For high risk loans it was slightly worse with a precision score of 0.85 and a recall score of 0.91 giving a F1 score of 0.88. The balanced accuracy score of this model was very good at 0.95.

* Machine Learning Model 2:
  * This model was excellent at predicting healthy loans with a precision score of 1.00, recall score of 0.99 and F1 score of 1.00. For high risk loans it was slightly worse with the same recall score but a precision score of 0.84 giving a F1 score of 0.91. The balanced accuracy score of this model was excellent at 0.99.

## Summary

* Both models performed exceptionally well when predicting healthy loans but there was a difference when predicting high risk loans
* The second model (trained with oversampled data) performed better predicting high risk loans and had a higher accuracy score
* Since we want to be able to identify high risk loans more than healthy loans, model 2 is the recommended model
