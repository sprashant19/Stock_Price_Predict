# 📈 Stock Price Predictor 

A simple stock price prediction project using **Linear Regression** and **historical stock data** from Yahoo Finance via `yfinance`.

## 🔍 Overview

This project demonstrates how to:

- Fetch real-time stock data (Apple Inc. - AAPL)
- Create lag-based features to predict the next day's closing price
- Train/test a linear regression model
- Visualize the predicted vs actual stock prices

## 📦 Tech Stack

- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- yfinance

## 📁 How it Works

1. Fetch 1 year of stock data using `yfinance`
2. Use the past 5 days' closing prices as input features
3. Train a `LinearRegression` model to predict the next day's close
4. Visualize performance with MSE and plot

## 📉 Sample Output

- **Mean Squared Error**: ~5.81
- On average, the prediction was off by around **$2–3**, which is reasonable for a basic model.

## 📊 Plot

Visual output showing predicted vs actual prices for the test set.

![image](https://github.com/user-attachments/assets/278995c4-e05a-4472-9837-71eebde68b37)
