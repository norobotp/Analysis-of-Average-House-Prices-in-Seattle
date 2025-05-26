# 🏘️ Analysis of Average House Prices in Seattle

This project explores trends and seasonality in average house prices across various neighborhoods in Seattle using time series analysis and forecasting methods.

## 🔍 Overview
We aimed to:
- Analyze historical price data from the Seattle housing market
- Decompose trends, seasonality, and irregular components
- Forecast future price patterns using SARIMA and exponential smoothing models

## 📈 Key Features
- **Data preprocessing**: Handling missing values, converting timestamps, and aggregating monthly averages
- **Decomposition**: Using STL (Seasonal and Trend decomposition using Loess)
- **Modeling**:
  - SARIMA (Seasonal ARIMA)
  - ETS (Error-Trend-Seasonal models)
  - AIC-based model selection and diagnostics
- **Visualization**: Plots for trend, seasonality, and prediction intervals

## 📁 Output
The HTML report includes:
- Data source description and summary statistics
- Visual decomposition of trends and seasonal cycles
- Model performance comparison
- 12-month forecast of average house prices by neighborhood

## ⚙️ Technologies Used
- `R`, `forecast`, `ggplot2`, `tsibble`, `fable`, `feasts`
- Time series forecasting and seasonal decomposition

---

## 💡 Motivation
This project was conducted as part of a graduate-level course at the University of Michigan to apply modern time series forecasting tools to real estate market data and derive actionable insights on price dynamics in Seattle.
