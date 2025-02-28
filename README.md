# -Time-Series-Analysis-and-Forecasting-of-Stock-Prices-Using-ARIMA-and-LSTM
# Time Series Analysis and Forecasting of Stock Prices Using ARIMA and LSTM

## Overview
This project analyzes and forecasts stock prices (e.g., Apple - AAPL) using historical data from Yahoo Finance. It employs two models: ARIMA (AutoRegressive Integrated Moving Average) for statistical time series forecasting and LSTM (Long Short-Term Memory) for deep learning-based prediction. The goal is to predict closing prices, compare model performance, and provide insights for investment strategies. The project is designed to be visually appealing, with clearly separated graphs and professional styling, and runs efficiently in Google Colab.

## Project Goals
- Predict stock prices using ARIMA and LSTM models.
- Evaluate model performance using metrics like RMSE, MAE, and MAPE.
- Visualize trends, forecasts, and model comparisons to identify patterns with enhanced, eye-catching graphics.
- Demonstrate advanced data science skills in time series analysis, statistical modeling, and deep learning.

## Dataset
- **Source**: Yahoo Finance via the `yfinance` library
- **Period**: January 1, 2018, to December 31, 2023 (configurable)
- **Features**: Close, Open, High, Low, Volume prices for the selected stock
- **No Manual Upload Required**: Data is fetched live using `yfinance`, requiring only an internet connection.

## Prerequisites
- Python 3.8 or higher
- Google Colab (recommended for running the code) or a local Python environment
- Required libraries:
  - `yfinance`
  - `statsmodels`
  - `tensorflow`
  - `pmdarima`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `sklearn`

## Installation
1. **Set Up Google Colab** (Recommended):
   - Open Google Colab (https://colab.research.google.com/).
   - Create a new notebook and run the following cell to mount your Google Drive and install dependencies:

     ```python
     # Mount Google Drive
     from google.colab import drive
     drive.mount('/content/drive')

     # Install dependencies
     !pip install yfinance statsmodels tensorflow pmdarima -q
