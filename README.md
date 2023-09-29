# Insurance Fraud Predictive Model
A machine learning project dedicated to predicting potential insurance fraud cases. This project leverages historical data to understand patterns and characteristics of fraudulent activities and implements models to predict future fraud instances.

## Table of Contents
1. [Introduction](#introduction)
2. [Data](#data)
3. [Techniques and Tools](#technique)
4. [Results](#result)
5. [Getting Started](#gettingstart)

## Introduction <a name="introduction"></a>
Insurance fraud is a significant concern in the insurance industry, leading to increased premiums and financial losses. This project aims to tackle this challenge by developing a predictive model to identify potential fraud cases, focusing on minimizing false alarms and maximizing true detections.

## Data <a name="data"></a>
The dataset used in this project comprises multiple features, including insured demographics, policy details, incident descriptions, and more. The target variable, ReportedFraud, indicates whether a given instance was reported as fraud.

## Techniques and Tools <a name="technique"></a>
Data Preprocessing: Merged and cleaned multiple datasets to produce a comprehensive dataframe suitable for analysis and modeling.
Feature Engineering: Conducted multicollinearity checks using Variance Inflation Factor (VIF) to ensure independent features.
Modeling: Implemented a Logistic Regression and Random Forest Classifier. Both models were optimized using GridSearchCV and trained with balanced class weights to handle data imbalance.
Tools & Libraries: Leveraged Python with Pandas, Numpy, and Scikit-learn for end-to-end data handling, modeling, and evaluation.

## Results <a name="result"></a>
The Random Forest Classifier achieved a precision of 99.93%, while the Logistic Regression model achieved a precision of 44.65%. These results highlight the capability of the developed models in accurately identifying potential fraud cases.

## Getting Started <a name="gettingstart"></a>
Clone this repository: git clone https://github.com/JustinLzc/Insurance-Fraud-Predictive-Model
Run the Jupyter Notebook: jupyter notebook Insurance Fraud Predictive Model.ipynb
