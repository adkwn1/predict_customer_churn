## Predict Customer Churn
Author: Andrew Kwon

## Description
This project trains and evaluates different models for a classification task (predict customer churn). Final evaluation metric of AUC-ROC with a threshold of 0.88 set by tasking company. Final AUC-ROC score of 0.91 achieved on test set. Exploratory data analysis and work plan developed for final project solution, conducted in two separate Jypter notebooks.

## Introduction
The telecom operator, Interconnect, would like to forecast churn of their clients.

**Problem Statement**: The company wants to forecast which users are planning to leave  
**Business Value**: To ensure loyalty, those who are going to leave will be offered with promotional codes and special plan options

Interconnect mainly provides two types of services:
1. Landline communication - the telephone can be connected to several lines simultaneously.
2. Internet - the network can be set up via a telephone line (*DSL*) or through a fiber optic cable. 

Other services the company provides include:
- Internet security via antivirus software (*DeviceProtection*) and a malicious website blocker (*OnlineSecurity*)
- A dedicated technical support line (*TechSupport*)
- Cloud file storage and data backup (*OnlineBackup*)
- TV streaming (*StreamingTV*) and a movie directory (*StreamingMovies*)
  
Our goal is to develop a model that will classify the customers into two groups; loyal customers that will stay with Interconnect, and customers that will churn. The target is the *EndDate* column. Values with a date signifies the date the customer left, whereas a "No" means the client is active. The final model quality will be based on its AUC-ROC score ($\ge$ 0.88), supplemented by F1 and accuracy.

## Datasets
- *contract.csv:* contract information
- *personal.csv:* the client's personal data
- *internet.csv:* information about Internet services
- *phone.csv:* information about telephone services

## Requirements
- pandas
- numpy
- matplotlib.pyplot
- sklearn.dummy
- sklearn.linear_model
- sklearn.tree
- sklearn.ensemble
- sklearn.preprocessing
- sklearn.metrics
- sklearn.utils
- sklearn.model_selection
- sklearn.compose
- lightgbm
- catboost
- imblearn.pipeline
- imblearn.over_sampling

## Screenshots
![5ae3efe9-1043-497a-b775-94b844b7ca87](https://github.com/adkwn1/predict_customer_churn/assets/119823114/923c6215-34b9-4830-9faf-1437498dc1af)
![80da0600-48c2-4564-9e28-48f014e99f6b](https://github.com/adkwn1/predict_customer_churn/assets/119823114/d0aafad9-4925-4244-b1c3-c1b2d72c72f8)
![6ecf53cf-05b8-4258-a065-de3513979175](https://github.com/adkwn1/predict_customer_churn/assets/119823114/a57fa1c1-78d4-4be6-889e-7addfcca28b2)
![eced413d-ef7a-493a-b929-9cb22a737d5e](https://github.com/adkwn1/predict_customer_churn/assets/119823114/cde0484e-4978-4a20-8ae6-81f9d3994819)
