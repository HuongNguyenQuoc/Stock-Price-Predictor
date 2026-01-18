# Stock-Price-Predictor
Using Ridge Regression to train the model
# 📈 Stock Price Predictor (Machine Learning)

A simple Machine Learning project that downloads historical stock data from **Yahoo Finance** and trains multiple regression models to predict the **Close price**.

> ⚠️ Disclaimer: This project is for learning purposes only and is **NOT** financial advice.

---

## ✨ Features
- Download stock price data automatically using **yfinance**
- Basic data exploration (shape, info, descriptive statistics)
- Visualizations:
  - Price time series plot
  - Distribution plots for Close/Open/High
- Train & compare multiple regression models:
  - **Linear Regression**
  - **Ridge Regression (L2 Regularization)**
  - **Lasso Regression (L1 Regularization)**
  - **Support Vector Regression (SVR) + GridSearchCV**
- Evaluation metrics:
  - **MSE**
  - **RMSE**
  - **R² Score**

---

## 🧠 Models Used
| Model | Purpose |
|------|---------|
| Linear Regression | Baseline model |
| Ridge Regression | Reduce overfitting by shrinking coefficients (L2) |
| Lasso Regression | Feature selection effect (L1) |
| SVR (RBF Kernel) | Non-linear regression, tuned via GridSearchCV |

---

## 📊 Dataset
The dataset is fetched from **Yahoo Finance** using `yfinance`.

The notebook downloads data like this:
- **Start date:** `2008-01-01`
- **End date:** `2026-01-17`
- `auto_adjust=True` (adjusted price)

Main columns usually include:
- Open, High, Low, Close, Volume  
(plus some extra columns depending on ticker)

---

## ⚙️ Tech Stack
- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- yfinance

---
