# Credit Risk Analysis

# Overview - Loan Prediction Risk Analysis
Jill, our colleague, has provided us an opportunity to conduct a machine learning model to predict credit card risk. Credit risk is typically an unbalanced problem because there are more good loans than their are bad, or risky. Because this information is vital for the company and it is unbalanced, we will need to use a multitude of techniques to train our supervised machine learning model. This documentation details how we built our supervised machine learning model, the results of each model, and our reccomendation on which model to use to predict credit card risk for Jill.

Data Source: our source was to large to upload to GitHub but was a CSV file with loan data from 2019 provided by LendingClub, a peer-to-peer lending service company.

We will utilize the following key libraries to build our model:
  - imbalanced-learn
  - scikit-learn
  
We will utilize the following algorithms to build our model:
  - RandomOverSampler: used in our "Oversampling" model
  - SMOTE: used in our "SMOTE Oversampling" model
  - ClusterCentroids: used in our "Undersampling" model
  - SMOTEEN: used in our "Combination Sampling" model
  - BalancedRandomForestClassifier: used in our "Forest Classifier" model
  - EasyEnsembleClassifier: used in our "AdaBoost Classification" model

# Results - 6 Machine Learning Models
## Oversampling
### Steps to Build Model
  1. Create training and target variables 
      a. Convert training variables to numerical values using get.dummies()
      b. Create target variables
      c. Check the balance of the target variables
  4. Resample the Training Data
      a. Make predictions using LogisticRegression classifier
      b. Calculate the accuracy score
      c. Create the confusion matrix
      d. Print the imbalanced classification report
      
### Findings
  
## SMOTE Oversampling
### Steps to Build Model

## Undersampling
### Steps to Build Model

## Combination Sampling
### Steps to Build Model

## Forest Classifier
### Steps to Build Model

## AdaBoost Classifier
### Steps to Build Model

# Summary

## Recommendation
