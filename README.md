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