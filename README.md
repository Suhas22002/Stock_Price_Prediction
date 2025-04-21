# 📈 Time Series Forecasting Case Study – Apple Stock Prices

This repository contains a case study focused on Time Series Forecasting of Apple stock prices using ARIMA/SARIMA models. The project walks through end-to-end data handling, modeling, forecasting, and evaluation processes.

# 📝 Problem Statement

Forecasting stock prices is one of the most common applications of time series analysis. In this case study, we aim to forecast Apple's stock prices (open, close, and volume) based on historical data from the NASDAQ exchange for periods spanning 2018 to 2019.

We will:
- Split the data into training and test sets.
- Build time series models using the training data.
- Forecast stock prices on test data timestamps.
- Evaluate model performance using RMSE (Root Mean Squared Error).

# 🔍 Topics Covered

- Exploratory Data Analysis (EDA)
- Time Series Modeling with:
  - ARIMA
  - SARIMA
  - With/without Exogenous Variables

# 📊 Data

The dataset includes historical Apple stock prices and is used to model and forecast future trends. The data covers:
- Opening Price
- Closing Price
- Trading Volume

## 📈 Modeling Approach

1. **ARIMA (AutoRegressive Integrated Moving Average):** A baseline model for time series data.
2. **SARIMA (Seasonal ARIMA):** Extension of ARIMA that accounts for seasonality.
3. **Exogenous Variables:** Testing models with additional external factors to improve forecast accuracy.

## 🧪 Evaluation

Model performance is assessed using the **Root Mean Squared Error (RMSE)**, which quantifies the average prediction error magnitude.

## 💡 Conclusion

This project demonstrates the effectiveness of classical time series models in forecasting financial time series and highlights the value of incorporating seasonality and external variables.

---
