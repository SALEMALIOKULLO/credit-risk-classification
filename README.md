# credit-risk-classification
Peer-to-peer lending services company building a model that can identify creditworthiness of borrowers.

# Module 20 Report Template

## Overview of the Analysis

## Purpose

The purpose of this analysis is to generate a model that will accurately distinguish between "healthy loans" and "high risk loans". Each applicant is identified based on apllication factors which include loan size, interest rate, the borrowers's income, debt to income ratio, number of accounts, derogatory marks, and total debt. First thing needed was to check the loan status then find the value count of the dataset which was roughly 75,036 applicants. We were then asssigned to split the data into training and testing datasets. Next step required us to make a logistic regression model with the training data to make predictions of the oringinal data and resampled data, Finally, done with all those steps we evaluated the models performance. 


## Results

* Machine Learning Model 1: (Original data) 

  * Accuracy: 99% (balanced accuracy score)
  * Precision: 85% (average for predicting high risk loans) and 100%(average for healthy loans).
  * Recall: 91% (average for high risk loans) and 99%(average for healthy loans).

* Machine Learning Model 2: (Resampled data)
    
  * Accuracy: 99% (balanced accuracy score)
  * Precision: 99% (healthy loans and high risk loans)
  * Recall: 99% (healthy loans and high risk loans)


## Summary

With the first Logistic Regression model, using the original data, it does very well at predicitng 'healthy loans' with accuracy, precision, and recall test data at 99%. However, when identifying 'high risk loans', it still does very well but noticably worse with precision score of 85% and recall score of 91%. This is likely related to the dataset imbalance with only about 3 percent of the apllicantions were considered high risk loanies. The second Logistic Regression model uses resampled data and perfroms noticably better at identifying the 'high risk loans'. 

Logistic Regression 2 seems to have fewer false predictions of testing data overall and would be the best model to use based on high accuracy. Based on the problem we are trying to solve, I would say it is more important to predict the '1's (high risk loans) because as a credit risk agency it is more important to disallow potential high risk loans based on the applicant factors. 


