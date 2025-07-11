# Multi-Company Financial Profit Margin Prediction

## Project Overview

This project performs advanced financial analysis and machine learning modeling on a multi-company dataset of US firms to predict **profit margins** based on key financial indicators. It demonstrates an end-to-end data science workflow including data preprocessing, clustering, model training and tuning, and model explainability.

## Features

- **Data Preprocessing:** Handles missing values and selects relevant financial features.  
- **Clustering:** Segments companies into distinct groups based on financial profiles using K-Means clustering.  
- **Modeling:** Compares multiple regression models including Random Forest, XGBoost, and Linear Regression.  
- **Hyperparameter Tuning:** Uses GridSearchCV to optimize model parameters.  
- **Explainability:** Applies SHAP values to interpret model predictions and feature importance.  
- **Visualization:** Includes plots for cluster distribution and actual vs predicted profit margins.

## Dataset

The dataset is sourced from a Kaggle financial statement dataset containing key financial metrics for approximately 200 US companies. It includes features such as EBITDA margins, operating cash flow, debt to equity ratio, market capitalization, and more.

## Getting Started

### Prerequisites

- Python 3.7 or higher  
- Packages: pandas, numpy, scikit-learn, xgboost, shap, matplotlib, openpyxl

Install the required packages using pip:

pip install pandas numpy scikit-learn xgboost shap matplotlib openpyxl

## Results

- Achieved strong predictive performance on profit margin with multiple models.  
- Identified key financial features influencing profitability using SHAP.  
- Successfully segmented companies into meaningful clusters based on financial health.
