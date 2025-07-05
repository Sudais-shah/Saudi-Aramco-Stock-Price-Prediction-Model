# 📈 Saudi Aramco Stock Price Prediction Model  

This project develops a robust and interpretable stock price prediction model using historical data and advanced feature engineering techniques. The final model—built with **Linear Regression**—demonstrates strong performance and stability, serving as a reliable baseline for future enhancements.  

---

## 🚀 Overview  
The goal is to forecast **next day stock closing prices** by leveraging historical market data enriched with engineered features such as lag values, rolling statistics, and technical indicators. Rigorous data preprocessing, exploratory analysis, and model evaluation were performed to ensure **high accuracy and generalizability**.  

---

## 🔑 Key Features  

### 🗃️ **Data Quality & Preprocessing**
- Comprehensive cleaning, including outlier removal and handling of missing values.  
- Conversion of the `Date` column to datetime format for proper time-series analysis.  
- Creation of a `Target` variable by shifting the `Close` price to predict the next day's value.  
- Removal of irrelevant features based on feature importance analysis.  

### ⚙️ **Feature Engineering**
- Added lag features, rolling means, rolling standard deviations.  
- Integrated technical indicators: **RSI**, **MACD**, **Bollinger Bands**, and more.  

---

## 🧠 Modeling & Evaluation  

- Models evaluated: **Linear Regression**, **Decision Tree**, and **Random Forest**.  
- Metrics used:  
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  
  - Mean Absolute Error (MAE)  
  - R² Score  
- Cross-validation confirmed stability across multiple folds.  

### 📊 **Final Model Performance: Linear Regression**
- **MSE:** 0.0775  
- **RMSE:** 0.2784  
- **R²:** 0.9771  
- **MAE:** 0.2037  

✅ **Linear Regression** outperformed Decision Tree and Random Forest, balancing simplicity, accuracy, and interpretability.  

---

## 🛠️ Usage  

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Sudais-shah/Saudi-Aramco-Stock-Price-Prediction-Model.git
