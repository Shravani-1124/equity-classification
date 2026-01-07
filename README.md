# Equity Classification

## Problem Statement
The goal of this project is to classify equities based on their financial performance using ML
The model uses financial ratios to predict the target equity class.

## Dataset
The dataset consists of financial statement information, including:
- Profitability ratios
- Liquidity ratios
- Leverage ratios
- Growth metrics

The cleaned dataset used for modeling is available in 'equity_cleaned.csv'.  
Raw data has been excluded from this repository.

## Approach
1. Choosing appropriate financial ratios to compute
2. Data cleaning and handling missing values
3. Financial ratio computation
4. Exploratory data analysis (EDA)
5. Feature selection based on correlation analysis
6. Train test split and Cross validation

## Model Evaluation
- Evaluation metric: ROC-AUC
- Mean cross-validated ROC-AUC: ~0.80.


 ## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn


