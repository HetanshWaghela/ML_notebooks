# 📘 Regression

This folder contains a comprehensive collection of notebooks demonstrating various regression techniques, including **Linear Regression**, **Polynomial Regression**, and regularized variants:

- **Ridge Regression**
- **Lasso Regression**
- **ElasticNet Regression**
- **Polynomial Regression** *(New)*

## 🧠 Algorithms Implemented

| Algorithm               | Description |
|-------------------------|-------------|
| **Linear Regression**   | Standard regression without regularization |
| **Ridge Regression**    | L2 regularization to penalize large coefficients |
| **Lasso Regression**    | L1 regularization to perform feature selection |
| **ElasticNet**          | Combines L1 and L2 regularization for balance |
| **Polynomial Regression** | Extends linear model by considering polynomial features |


## 📂 Files Included

- `linear_lasso_ridge_elasticnet.ipynb` – Main notebook covering linear, ridge, lasso, and elastic net regressions  
- `polynomial_regression.ipynb` – New notebook for polynomial regression
- `HousingData.csv`- Dataset used in the linear,ridge,lasso and elastic net regressions
- `enhanced_car_efficiency_data.csv` – Dataset used in the polynomial regression notebook




## 🔍 Workflow

- 📌 Exploratory Data Analysis (EDA)  
- ⚙️ Feature Scaling  
- ✨ Model Training & Evaluation (with train-test split)  
- 📈 Coefficient Analysis & Regularization Effects  
- 📉 RMSE and R² score comparison across models  
- 🔎 VIF (Variance Inflation Factor) to check multicollinearity  


## 🛠 Requirements

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```
