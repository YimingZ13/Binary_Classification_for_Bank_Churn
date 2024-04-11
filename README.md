# Binary_Classification_for_Bank_Churn

## Table of Contents
1. [Introduction](#Introduction)
2. [File Structure](#FileStructure)
3. [Installing](#Installing)
4. [Feature Documentations](#FeatureDocumentations)
5. [Key Results](#KeyResults)
6. [Authors](#Authors)
7. [License](#License)

<a name="Introduction"></a>
## Introduction

Welcome to the Bank Customer Churn Prediction Project repository. In this project, we focus on leveraging machine learning techniques to predict bank customer churn. Churn prediction is crucial for banks to identify potential leavers early and formulate strategies to retain them, thereby ensuring customer satisfaction and loyalty, which are key to a bank's profitability.

Customer churn, also known as customer attrition, refers to when a customer (e.g., a bank account holder) decides to end their relationship with the bank. Early identification of churn can enable proactive customer retention strategies, enhancing customer value and reducing turnover costs.

This project utilizes a binary classification approach, where we aim to classify bank customers into two groups: those likely to churn and those likely to stay. Through comprehensive data analysis and the application of various machine learning models, we seek to accurately predict customer churn based on historical data.

The dataset used in this project contains information on bank customers, including demographic data, account details, and transaction behaviors. Key features include age, gender, account balance, credit score, tenure, and product usage. The target variable is a binary attribute indicating whether the customer has churned.

The [original datasets](https://www.kaggle.com/datasets/shubhammeshram579/bank-customer-churn-prediction).

<a name="FileStructure"></a>
## File Structure
Each of the following project steps is completed in a separate notebook:
- [Data Cleaning and EDA](https://github.com/YimingZ13/Binary_Classification_for_Bank_Churn/blob/main/bank_churn_EDA.ipynb): `bank_churn_EDA.ipynb`
- [Data Preprocessing](https://github.com/YimingZ13/Binary_Classification_for_Bank_Churn/blob/main/bank_churn_preprocessing.ipynb): `bank_churn_preprocessing.ipynb`
- [Modelling](https://github.com/YimingZ13/Binary_Classification_for_Bank_Churn/blob/main/bank_churn_modelling.ipynb): `bank_churn_modelling.ipynb`

<a name="Installing"></a>
## Installing
There are no special packages needed for this project, most of packages come with the Anaconda distribution of Python 3.

<a name="FeatureDocumentations"></a>
## Feature Documentations
`train.csv`:
- `Customer ID`: A unique identifier for each customer
- `Surname` : The customer's surname or last name
- `Credit Score` : A numerical value representing the customer's credit score
- `Geography` : The country where the customer resides (France, Spain or Germany)
- `Gender`: The customer's gender (Male or Female)
- `Age`: The customer's age
- `Tenure`: The number of years the customer has been with the bank
- `Balance`: The customer's account balance
- `NumOfProducts`: The number of bank products the customer uses (e.g., savings account, credit card)
- `HasCrCard`: Whether the customer has a credit card (1 = yes, 0 = no)
- `IsActiveMember`: Whether the customer is an active member (1 = yes, 0 = no)
- `EstimatedSalary`: The estimated salary of the customer
- `Exited`: Whether the customer has churned (1 = yes, 0 = no)
  
<a name="KeyResults"></a>
## Key Results
- The best performed model was LightGBM with RandomUnderSampler.
- The model achieved 0.89 ROC-AUC score

<a name="Authors"></a>
## Authors
Yiming Zhao | [LinkedIn](https://www.linkedin.com/in/yiming-zhao13/)

<a name="License"></a>
## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
