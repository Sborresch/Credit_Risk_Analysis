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
      - Convert training variables to numerical values using get.dummies()
      - Create target variables
      - Check the balance of the target variables
  4. Resample the Training Data
      - Make predictions using LogisticRegression classifier
      - Calculate the accuracy score
      - Create the confusion matrix
      - Print the imbalanced classification report
      
### Findings
#### Accuracy Score
![Screenshot](https://github.com/Sborresch/Credit_Risk_Analysis/blob/main/Oversampling/Accuracy_Score.png)

It is important to note the accuracy rate of each machine learning model as this is what will provide justification for using this model. According to Kirsten Barkved from the [obviously.ai company](https://www.obviously.ai/post/machine-learning-model-performance#:~:text=Good%20accuracy%20in%20machine%20learning,not%20only%20ideal%2C%20it%27s%20realistic.), an accuracy rate above 70% is great model performance. Therefore, we should look at accuracy scores within the 70%-100% range.

This machine learning model shows a 65% accuracy rate, which falls below our chosen accuracy range. For this reason, we will not use this model for our credit-risk prediction project.

#### Confusion Matrix
![Screenshot](https://github.com/Sborresch/Credit_Risk_Analysis/blob/main/Oversampling/Confusion_Matrix.png)

The confusion matrix can be complicated in understanding. However, a simple graph from [Anuganti Suresch from the Medium company](https://medium.com/analytics-vidhya/what-is-a-confusion-matrix-d1c0f8feda5) shows how to understand this matrix.

#### Classification Report
![Screenshot](https://github.com/Sborresch/Credit_Risk_Analysis/blob/main/Oversampling/Confusion_Matrix.png)
  
## SMOTE Oversampling
### Steps to Build Model
  1. Create training and target variables 
      - Convert training variables to numerical values using get.dummies()
      - Create target variables
      - Check the balance of the target variables
  4. Resample the Training Data
      - Make predictions using LogisticRegression classifier
      - Calculate the accuracy score
      - Create the confusion matrix
      - Print the imbalanced classification report
      
### Findings
#### Accuracy Score

#### Confusion Matrix

#### Classification Report

### Steps to Build Model
  1. Create training and target variables 
      - Convert training variables to numerical values using get.dummies()
      - Create target variables
      - Check the balance of the target variables
  4. Resample the Training Data
      - Make predictions using LogisticRegression classifier
      - Calculate the accuracy score
      - Create the confusion matrix
      - Print the imbalanced classification report
      
### Findings
#### Accuracy Score

#### Confusion Matrix

#### Classification Report

## Combination Sampling
### Steps to Build Model

## Forest Classifier
### Steps to Build Model

## AdaBoost Classifier
### Steps to Build Model

# Summary

## Recommendation
