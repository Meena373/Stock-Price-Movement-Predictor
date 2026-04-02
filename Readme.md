# 📈 Stock Price Movement Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the **next-day stock price movement (Up/Down)** using Machine Learning techniques.
A **Random Forest Classifier** is trained on historical stock data along with technical indicators to forecast whether the stock price will increase or decrease.

The model uses data fetched from Yahoo Finance and applies feature engineering to capture market trends.

---

## 🚀 Features

* Real-time stock data using Yahoo Finance API
* Machine Learning model (Random Forest)
* Feature engineering with technical indicators
* Predicts next-day stock movement (Up/Down)
* Time-series based training (no data leakage)

---

## 🧠 How It Works

1. Historical stock data is fetched using `yfinance`
2. Technical indicators are created:

   * Daily Return
   * Moving Averages (10-day & 50-day)
   * Price Change
   * Volatility
3. A **target variable** is defined:

   * `1` → Price goes UP
   * `0` → Price goes DOWN
4. Data is split into training and testing sets
5. A **Random Forest model** is trained
6. The model predicts the next day's stock movement

---

## 📊 Features Used

* Return
* MA10 (10-day Moving Average)
* MA50 (50-day Moving Average)
* Price Change
* Volatility

---

## 🛠️ Tech skills

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* yfinance
* Matplotlib (optional for visualization)

---

## ▶️ Example Output

```id="g2p6gk"
Model Accuracy: 0.62

Latest Date: 2026-03-08
Latest Closing Price: 175.23

Prediction for Next Trading Day:
📈 Stock Price will go UP
```

---

## 📈 Model Details

* Algorithm: Random Forest Classifier
* Evaluation Metric: Accuracy Score
* Train-Test Split: 80% / 20% (time-series based)

---

## 📌 Key Learnings

* Time series data handling
* Feature engineering with financial indicators
* Avoiding data leakage in ML models
* Building classification models for real-world problems

---

## 📈 Future Improvements

* Add more technical indicators (RSI, MACD)
* Hyperparameter tuning
* Use LSTM / Deep Learning models
* Build a Streamlit dashboard
* Predict stock prices instead of direction

