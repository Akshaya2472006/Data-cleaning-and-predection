# Data Cleaning & Predection

## Project Overview
This project focuses on preparing and analyzing the Churn_Modelling dataset, which contains customer information for a bank. The goal is to:

Clean and preprocess the raw dataset.

Build predictive models to understand customer churn behavior.

The repository includes two main notebooks:

------

## Files
Data Cleaning.ipynb

Loads the dataset using pandas.

Inspects structure with .info() and .head().

Handles missing values and removes duplicates.

Encodes categorical variables (Geography, Gender).

Drops irrelevant columns (RowNumber, CustomerId, Surname).

Scales numerical features for modeling.

Data Prediction.ipynb

Uses scikit-learn for preprocessing and modeling.

Demonstrates feature scaling (StandardScaler, MinMaxScaler).

Handles missing values with mean imputation.

Prepares subsets of data (e.g., Age, Tenure) for experimentation.
-----

## Requirements

Install dependencies before running the notebooks:
 pip install pandas numpy scikit-learn matplotlib
-----

## Usage
Clone the repository:

git clone https://github.com/YourUsername/Data-cleaning-and-prediction.git
cd Data-cleaning-and-prediction
Open the notebooks in Jupyter or Google Colab.

Run Data Cleaning.ipynb first to preprocess the dataset.

Run Data Prediction.ipynb to apply machine learning models.
----

## Dataset
The dataset Churn_Modelling.csv contains 10,000 customer records with the following key features:

Demographics: Age, Gender, Geography

Account Info: CreditScore, Balance, Tenure, NumOfProducts

Behavior: HasCrCard, IsActiveMember

Target: Exited (1 = churned, 0 = retained)
-------

## Goals
Understand customer churn patterns.

Build a clean dataset ready for ML models.

Experiment with scaling and feature engineering.

Provide a reproducible workflow for churn prediction.
-----

## Author

Akshaya A

BCA-Kamaraj College



