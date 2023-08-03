# Credit Risk Modelling in Python

This repository is based on the Medium article ["Credit Risk Modelling in Python"](https://medium.com/mlearning-ai/credit-risk-modelling-in-python-7b21a0b794b1) by Rahul Sisodia. 

## Overview

Credit risk is the potential for a borrower to fail to meet their debt obligations. Financial institutions are increasingly relying on technology to predict which customers are most likely to default. This project aims to build a model that can predict the likelihood of credit card default.

## Credit Risk Modelling

Credit risk modelling involves using data models to determine:

1. The probability of a borrower defaulting on a loan.
2. The financial impact on the lender if a default occurs.

## Model Construction

The model is constructed through the following steps:

1. Data Preparation and Pre-processing
2. Feature Engineering and Selection
3. Model Development and Model Evaluation

## Data

The dataset used in this project is sourced from Kaggle and includes variables such as:

- Amount of given credit
- Gender
- Education
- Marital status
- Age
- History of past payment
- Amount of bill statement
- Amount of previous payment

## Data Preparation and Pre-processing

The initial dataset consists of 25 attributes. It is crucial to clean and format the data appropriately before developing any machine learning model.

## Data Visualization

The project includes various data visualizations, including the target variable, education column, age column distribution, sex column, and a scatter plot.

## Feature Scaling

Feature scaling is the process of scaling or transforming all of the variables in our dataset to a given scale. This is necessary for the proper functioning of certain machine learning algorithms.

## Train Test Split

The dataset is split into two groups: the training set and the test set.

## Class Imbalance

The Synthetic Minority Oversampling Technique (SMOTE) is used to address class imbalance in the dataset. SMOTE oversamples the minority class by creating "synthetic" examples.

## Model Building

The models used in this project include Logistic Regression, Random Forest Classifier, and XGBoost Classifier. The project also utilizes cross-validation.

## Reference

This project is based on the Medium article ["Credit Risk Modelling in Python"](https://medium.com/mlearning-ai/credit-risk-modelling-in-python-7b21a0b794b1) by Rahul Sisodia.
