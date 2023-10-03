# CreditRiskFeatureSelection
An exploratory Python project implementing Forward Selection and Backward Elimination feature selection techniques on a credit card default dataset.


## Project Description
This project explores the application of feature selection techniques - Forward Selection and Backward Elimination - on a credit card default dataset. Feature selection methods help to identify and remove unnecessary features from the data, which can improve the efficiency and performance of a predictive model. This repository contains a comprehensive Python script that provides a step-by-step approach to applying these techniques on the dataset.

## Dataset Overview
The dataset contains information about credit card clients, including their demographic details, credit data, history of payment, and default payments. The target variable indicates whether a client will default payment next month.

## Techniques Implemented
- **Forward Selection**: The model starts with no variables and iteratively adds variables based on their statistical significance.
  
- **Backward Elimination**: The model starts with all variables and iteratively removes variables based on their statistical significance.

## How to Use
1. Download the Python script from the repository.
2. Replace the dataset path in the script with the path on your local machine.
3. Run the script to observe the results of the feature selection methods.

## Requirements
- Python 3.
- Pandas
- Scikit-learn



## Acknowledgements
Dataset: https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients
