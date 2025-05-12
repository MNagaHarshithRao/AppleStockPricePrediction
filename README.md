
# 🍎 Apple Stock Price Prediction Using LSTM

This project uses a Long Short-Term Memory (LSTM) neural network to predict the stock prices of Apple Inc. (AAPL). The goal is to leverage historical stock data to forecast future prices using a deep learning model.

## 📈 Overview

Stock price prediction is a challenging task due to the market's volatile and non-linear nature. LSTM models are well-suited for time series prediction due to their ability to capture temporal dependencies in sequential data.

This repository demonstrates:
- Data collection and preprocessing
- LSTM model creation and training
- Evaluation and visualization of predictions

## 🧠 Model

We use a deep LSTM network with:
- Input: sequences of past stock prices (e.g., 60 days)
- Output: the next predicted closing price
- Layers: LSTM layers with dropout for regularization
- Loss function: Mean Squared Error (MSE)
- Optimizer: Adam

## 📊 Dataset

- **Source**: [Yahoo Finance](https://finance.yahoo.com/quote/AAPL/)
- **Data Used**: Historical Apple stock prices (Date, Open, High, Low, Close, Volume)
- **Date Range**: Customizable (default: last 5–10 years)

## 📁 Project Structure

