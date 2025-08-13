# 🏠 Housing Price Prediction Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0%2B-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📝 Project Description
A machine learning regression analysis comparing various algorithms to predict housing prices based on property features. The project includes extensive exploratory data analysis (EDA), feature engineering, and model evaluation.

---

## 📊 Dataset Overview
- **Rows:** 545 property listings  
- **Target Variable:** `Price` (continuous)  
- **Features:**
  - **Continuous:** `Area` (sq ft)  
  - **Discrete:** `Bedrooms`, `Bathrooms`, `Stories`, `Parking`  
  - **Binary:** `Mainroad`, `Guestroom`, `Basement`, `Hotwaterheating`, `Airconditioning`, `Prefarea`  
  - **Categorical:** `Furnishingstatus` (3 categories)  

---

## 🤖 Models Implemented

| Model Type       | Best Model            | R² Score | MAE       | RMSE      |
|-----------------|---------------------|----------|-----------|-----------|
| Linear           | Multiple Regression  | 0.6811   | 884,725   | 1,217,248 |
| Regularized      | Lasso (α=613.59)    | 0.6810   | 884,882   | 1,217,382 |
| Tree-Based       | Random Forest        | 0.7357   | 665,540   | 869,066   |
| Ensemble         | XGBoost              | 0.6921   | 691,089   | 938,031   |
| Distance-Based   | kNN (k=15)           | 0.7204   | 665,066   | 893,838   |

---

## 📈 Key Findings
- **Best Performing Model:** Random Forest (R²: 0.7357)  
- **Most Important Features:**
  - Property area (strongest predictor)
  - Number of bathrooms
  - Presence of air conditioning
  - Number of stories
- **Feature Engineering:** Binary encoding improved model performance by 12% compared to one-hot encoding
