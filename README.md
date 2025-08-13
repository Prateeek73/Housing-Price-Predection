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

## 🛠️ Installation
```bash
git clone https://github.com/yourusername/housing-price-prediction.git
cd housing-price-prediction
pip install -r requirements.txt
