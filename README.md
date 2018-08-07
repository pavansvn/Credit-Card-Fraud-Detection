# Credit-Card-Fraud-Detection
Problem Statement:
The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. This model is then used to identify whether a new transaction is fraudulent or not. Our aim here is to detect 100% of the fraudulent transactions while minimizing the incorrect fraud classifications.

DataSet :
The dataset that is used for credit card fraud detection is derived from the following Kaggle URL :
https://www.kaggle.com/mlg-ulb/creditcardfraud

Observations
The data set is highly skewed, consisting of 492 frauds in a total of 284,807 observations. This resulted in only 0.172% fraud cases. This skewed set is justified by the low number of fraudulent transactions.
The dataset consists of numerical values from the 28 ‘Principal Component Analysis (PCA)’ transformed features, namely V1 to V28. Furthermore, there is no metadata about the original features provided, so pre-analysis or feature study could not be done.
The ‘Time’ and ‘Amount’ features are not transformed data.
There is no missing value in the dataset.

Introduction
I will be using various predictive models to see how accurate they are in detecting whether a transaction is a normal payment or a fraud. As described in the dataset, the features are scaled and the names of the features are not shown due to privacy reasons. Nevertheless, we can still analyze some important aspects of the dataset. Let's start!

Goal:
Understand the little distribution of the "little" data that was provided to us. 
Create a 50/50 sub-dataframe ratio of "Fraud" and "Non-Fraud" transactions. (NearMiss Algorithm) 
Determine the Classifiers we are going to use and decide which one has a higher accuracy. 
Understand common mistaked made with imbalanced datasets. 
Anomaly detection  to identify unusual patterns  called outliers using the Isolation Forest, Density based, SVM detection algorithms.
