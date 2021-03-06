# Credit Card Fraud Detection using Classification

## Group Partners:
Samantha Soendoro (ssoendoro@ucdavis.edu)

Jordan Brennan (jdbrennan@ucdavis.edu)

Kideok Kwon (kidkwon@ucdavis.edu)

Yuyan Li (yuyli@ucdavis.edu)

## Dataset Link: 
https://www.kaggle.com/mlg-ulb/creditcardfraud

## Description of Project:
The goal of the project is to use a large dataset of credit card transactions to try and create an accurate and computationally feasible model to predict Fraudulent Transactions. This will be done through analysis of the given 30 possible predictor variables and experimenting with various classification algorithms to achieve the highest accuracy as possible. 

As with many fraud-related data science projects, this dataset has an interesting feature where the data is highly imbalanced between the 2 classes (Fraud, Not Fraud). We will experiment with ways to deal with this imbalance. Additionally, because this dataset deals with confidential data, the predictor variables are unnamed. Thus, it will require more rigorous and technical analysis instead of intuition.

## Description of Dataset:
We will be using 284,807 rows of Credit Card transactions with 31 columns, 1 target variable (class of yes or no for fraud) and 30 possible predictor variables. The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days

Credit: The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection.

## Key Questions:
How do we deal with such an imbalanced dataset? What undersampling methods can we explore?
How do we choose which predictors to use and which not to, and what are efficient methods to test various combinations of these predictors?
Which Classification method works best for this dataset, in terms of computational speed and accuracy?

## Methodologies to be used:
Data Cleaning/Processing: Imputing, Undersampling, etc

Analysis: Canonical correlation analysis, ANOVA, etc

Modeling: Logistic regression, LDA, Tree Methods, SVM.
