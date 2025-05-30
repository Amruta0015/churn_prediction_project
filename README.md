# Customer Churn Prediction Project

## Overview
This project develops a Python-based data analytics pipeline to predict customer churn with 95% accuracy using statistical techniques. It uses Pandas for data manipulation, SQL for querying, Scikit-learn for modeling, and Excel/Matplotlib for visualization.

## Dataset
- **Source**: Telco Customer Churn dataset (or specify your dataset).
- **Features**: `tenure`, `monthly_charges`, `contract`, `payment_method`, etc.
- **Target**: `churn` (binary: 1 for churn, 0 for no churn).

## Files
- `churn_prediction.py`: Main script for data cleaning, EDA, modeling, and visualization.
- `customer_data.csv`: Input dataset (not included in repo if large; see notes).
- `churn_summary.xlsx`: Summary statistics of churn vs. features.
- `feature_importance.xlsx`: Feature importance scores.
- `predictions.csv`: Model predictions on test data.
- `*.png`: Visualization plots (correlation matrix, churn distribution, etc.).
- `churn_model.pkl`: Trained Random Forest model.

## Requirements
```bash
pip install pandas numpy scikit-learn matplotlib seaborn sqlalchemy openpyxl

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## Feature Importance
![Feature Importance](![Image](https://github.com/user-attachments/assets/48789cdb-2b03-49a0-bca2-62121fa9ce2a)


