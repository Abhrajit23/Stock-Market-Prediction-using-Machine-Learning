# 📈 Stock Market Prediction using Machine Learning  
**By:** Abhrajit Das  

## 🔍 Project Overview  
This project applies machine learning classification algorithms to predict the directional movement of a stock's closing price. It uses historical market data with features like adjusted opening/closing prices, highs, lows, and engineered volatility-based metrics to build predictive models.

## 🧠 Problem Statement  
Stock markets are volatile and influenced by countless variables. Traders and analysts often rely on statistical tools to forecast price trends. This project simplifies that approach by using machine learning to classify whether a stock’s price will go up or down.

## ✅ Solution  
We designed a pipeline that performs:  
- Data cleaning and preprocessing without removing natural outliers  
- Feature engineering with adjusted price metrics and percentage changes  
- Binary classification using multiple algorithms  
- Performance comparison using accuracy scores and classification reports  

## 📂 Dataset  
**Source:** Historical stock market CSV file  

**Features used:**  
- Adjusted Open, High, Low, Close  
- Percentage change (`Pct_change`)  
- Volatility (`High - Low`)  
- Price movement label (1: Up, 0: Down)  

## 🤖 Models Implemented  
- K-Nearest Neighbors (KNN)  
- Random Forest Classifier  
- Gradient Boosting Classifier  
- Support Vector Machine (SVM)  
- XGBoost  

## 📊 Results  
Each model was evaluated based on classification accuracy. Feature correlation heatmaps and prediction outputs provided clarity on model performance.

## 🚀 Tools & Technologies  
- Python  
- Pandas, NumPy, Seaborn, Matplotlib  
- Scikit-learn  
- XGBoost  

## 📌 Key Insight  
Machine learning can assist in pattern recognition across financial data. This project demonstrates how model performance varies with stock volatility and feature selection — paving the way for further research into algorithmic trading.
