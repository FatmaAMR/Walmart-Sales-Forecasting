# 📊 Walmart Sales Forecasting Tool

This project predicts future Walmart sales based on historical weekly sales data.  
It was developed as part of a **Kaggle time-series forecasting challenge** and includes both **data analysis** and a deployed **interactive interface**.

---

## 🚀 Project Overview
The goal of this project is to forecast weekly sales for different Walmart stores and departments using:
- **Time-based feature engineering** (lags, rolling averages, month/week/day features)
- **Seasonal decomposition** to analyze trends and seasonality
- **Regression models** including XGBoost and LightGBM
- **Interactive Gradio interface** for user-friendly predictions

---

## 🛠️ Features
- **Exploratory Data Analysis (EDA):** Identified patterns, seasonality, and trends in sales.  
- **Feature Engineering:** Created lag features, rolling averages, and time-based attributes.  
- **Modeling:** Applied regression models (XGBoost/LightGBM) with time-aware validation.  
- **Forecasting:** Predicted future sales for selected Store and Department.  
- **Deployment:** Gradio interface for real-time predictions.  


---

## ⚙️ How It Works
1. **Input:** Store ID, Department ID, and Date  
2. **Model:** Trains on all historical sales data with engineered features  
3. **Output:** Predicted weekly sales for the given Store & Department  

---

## 🖼️ Interface Preview
<img width="1890" height="628" alt="image" src="https://github.com/user-attachments/assets/47c22500-d3e9-4e5d-96bd-c87c37fdd7cf" />

---

## 📦 Requirements
- Python 3.8+
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- xgboost, lightgbm
- statsmodels
- gradio

---

## 📊 Example
**Input:**  
- Store ID: `1`  
- Department ID: `1`  
- Date: `2012-01-07`  

**Output:**  
Predicted Weekly Sales for Store 1, Dept 1: 42,305.77

