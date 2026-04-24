# Big Mart Sales Prediction

A machine learning project that predicts the sales of products at Big Mart outlets using regression techniques.

## Problem Statement
Big Mart wants to predict outlet-level product sales to help with inventory management and planning. Given product and store attributes, the model predicts the sales figure.

## Dataset Features
- Item weight, fat content, visibility, type, MRP
- Outlet size, location type, type, establishment year

## Approach
- Exploratory Data Analysis (EDA)
- Missing value treatment
- Label encoding & feature engineering
- Model training using XGBoost / Random Forest Regressor

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn

## How to Run
```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn jupyter
jupyter notebook Big_mart_Sales_Prediction.ipynb
```

## Results
The model achieves strong predictive performance on the test set using RMSE as the evaluation metric.

## Author
**Divyansh Nag** | [GitHub](https://github.com/Divyanshnag) | dnag9936@gmail.com
