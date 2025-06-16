# Linear Regression Forecasting (Mini Project)
This project is a small but significant step in my broader exploration of quantitative finance and time series modeling. It aims to build a simple, interpretable forecasting model using linear regression applied to historical stock price data.

## Objective
The goal of this mini project is to apply fundamental regression techniques to time series data, focusing on using lagged stock prices to predict the next day's closing price. It serves as a baseline model to compare future, more complex models.

## Tools & Libraries
- **Python**
- **pandas** – for data processing
- **numpy** – for numerical operations
- **matplotlib** / **seaborn** – for visualizations
- **scikit-learn** – for regression modeling and evaluation

## Methodology

1. **Data Acquisition**
   - Imported historical stock prices through yfinance

2. **Feature Engineering**
   - Created lag features: past 5 days of prices (`Lag_1` to `Lag_5`)

3. **Data Splitting**
   - Train/test split 30%

4. **Model Building**
   - Linear regression with scikit-learn
   - Target variable: current day’s price
   - Features: price lags

5. **Evaluation**
   - Compared model predictions with actual prices
   - Plotted results for visual inspection
