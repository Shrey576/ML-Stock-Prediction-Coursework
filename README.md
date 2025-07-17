# ML-Stock-Prediction-Coursework
Developed a machine learning project using LSTM-CNN models to predict stock values of the S&amp;P500 using an open-source dataset. The model was compared with Random Forest which was used as a comparable. ARIMA was also used a simple benchmark to gage both model performances against.

- Got 80%

# 📈 Stock Price Prediction with Random Forest, CNN-LSTM, and Naive Benchmark

This project demonstrates the use of machine learning and deep learning models to predict stock prices using historical data. It compares the performance of three approaches:

- 🌲 **Random Forest Regressor** — a tree-based ensemble model
- 🤖 **CNN-LSTM** — a hybrid deep learning model combining convolutional and recurrent layers
- 🧠 **Naive Benchmark** — a simple baseline that assumes the next price is the same as the last

Predictions are evaluated using standard metrics like **Mean Squared Error (MSE)** and **R-squared (R²)**, and visualized for comparison.

---

## 📦 Features

- 📊 Uses a historical stock dataset (`all_stocks_5yr.csv`)
- 🌲 Implements **Random Forest** with 100 trees and max depth of 10
- 🤖 Implements **CNN-LSTM** for time-series sequence modeling
- 🧠 Implements a **Naive model** (predicts the previous price)
- 📏 Uses `MinMaxScaler` to normalize input features
- 🔁 Inverse transforms predictions to original scale
- 📈 Saves and plots actual vs predicted prices for all models
- 🧪 Outputs MSE and R² for fair model comparison

---

## 🔧 Requirements

Install the required Python packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow
