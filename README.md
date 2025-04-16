# DeepDataHack
# 🛍️ Local Retail Demand Forecasting for Kirana Stores

## 🚀 Problem Statement
Predicting high-value retail orders to optimize inventory and revenue strategies.

## 📊 Dataset
Retail sales data with invoice, quantity, unit price, customer ID, etc.

## 🧠 Approach
- Feature Engineering
- New target: IsHighValue (Top 5% orders by total value)
- Ensemble Model: XGBoost + CatBoost + RandomForest (Soft Voting)
- SMOTE / Undersampling to handle imbalance

## 🧪 Metrics
- F1 Score: 0.9984689671416794
- AUC-ROC: 0.9989982877271185
- Accuracy: 0.9989786297925832
- Confusion Matrix, ROC Curve

## 🔍 Explainability
- SHAP Summary Plot
- Feature Importance

## ⚡ Bonus
- Dask for large dataset handling
- Custom Ensemble
- Advanced feature engineering

## 📁 How to Run
Colab-compatible. Upload CSV and run all cells.
