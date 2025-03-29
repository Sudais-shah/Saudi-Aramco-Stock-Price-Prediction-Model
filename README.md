# Saudi-Aramco-Stock-Price-Prediction-Model
This project aims to develop a robust and interpretable stock price prediction model using historical data and advanced feature engineering techniques. The final model—built with Linear Regression—demonstrates exceptional performance and stability, and serves as a strong baseline for future enhancements.

## Overview
The goal of this project is to forecast stock closing prices by leveraging historical market data enriched with engineered features such as lag values, rolling statistics, and technical indicators. Rigorous data preprocessing, exploratory analysis, and model evaluation have been performed to ensure high accuracy and generalizability.

## Key Features
Data Quality & Preprocessing:

Comprehensive cleaning, including outlier removal and handling of missing values.

Conversion of the Date column to datetime format for proper time-series analysis.

Removal of irrelevant features based on feature importance analysis.

## Feature Engineering:

Integration of essential features like lag values, rolling means, standard deviations, and technical indicators (e.g., RSI, MACD, Bollinger Bands) directly within the dataset.

## Modeling & Evaluation:

Multiple models were evaluated, including Linear Regression, Decision Tree, and Random Forest.

Performance metrics such as Mean Squared Error, Root Mean Squared Error, Mean Absolute Error, and R² were used to assess model performance.

Cross-validation confirmed model stability across different time splits.

## Final Model & Deployment:

Linear Regression demonstrated the best performance, with an R² of nearly 1.0 and minimal error.

The final model is saved using Joblib for future deployment.

## Results
Linear Regression Performance:

MSE: 0.01

RMSE: 0.12

R²: 1.00

MAE: 0.09

## Model Comparison:
Linear Regression outperformed both the Decision Tree and Random Forest models in terms of error metrics, confirming its reliability for this dataset.

## Future Work
Deep Learning Integration:
Future enhancements will include exploring advanced deep learning techniques (such as LSTM and GRU models) to capture complex time-series patterns.

## External Data Sources:
Incorporating external market factors like macroeconomic indicators and sentiment analysis from news sources to further improve forecasting accuracy.

## Hyperparameter Optimization:
Although Linear Regression did not require extensive tuning, more complex models may benefit from automated hyperparameter tuning.

## Usage
1 - Clone the Repository: git clone https://github.com/yourusername/stock-price-prediction.git
2 - Install Dependencies: pip install -r requirements.txt
**Run the Notebook:** Open Stock_Price_Prediction.ipynb in Jupyter Notebook and follow the documented steps.

## Deploy the Model: 
The final model is saved as linear_regression_model.pkl and can be deployed using FastAPI or similar frameworks for real-time predictions.

## Conclusion
This project successfully demonstrates the end-to-end process of developing a stock price prediction model—from data preprocessing and feature engineering to model training, evaluation, and deployment. The exceptional performance of the Linear Regression model, coupled with thorough cross-validation, makes it a reliable foundation for future enhancements.

