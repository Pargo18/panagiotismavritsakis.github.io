---
layout: single
title: "Commodities Price Forecasting"
permalink: /projects/commodities-forecasting/
---

Can we anticipate the price of oil, gas, and metals? This project dives into the volatile world of commodity markets using predictive models to forecast prices based on historical trends and macroeconomic indicators.

It’s a practical exercise in time series forecasting, economic intuition, and the power of machine learning for decision support in finance and resource planning.

## Project Highlights

- 📊 **Time Series Forecasting**: Focuses on daily and monthly price movements for key commodities.
- 🔍 **Feature Engineering**: Includes lag features, rolling statistics, and external indicators like exchange rates or inflation.
- ⚖️ **Model Comparison**: Tests traditional models (ARIMA) against machine learning methods like XGBoost and LSTM networks.
- 📈 **Forecast Evaluation**: Analyzes accuracy and volatility handling using metrics like MAE, RMSE, and custom economic indicators.

## Tech Stack

- **Data Sources**: EIA, World Bank, Yahoo Finance
- **Forecasting Methods**: ARIMA, XGBoost, LSTM (Keras)
- **Data Wrangling**: Pandas, NumPy
- **Visualization**: Seaborn, Plotly

## Key Insights

- Machine Learning models handle nonlinear relationships better but can overfit without proper tuning.
- Classic models still perform surprisingly well on stable commodities like gold.
- Ensemble approaches combining forecasts tend to improve robustness and reliability.
