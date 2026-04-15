# 📈 Stock Price Forecasting using ARIMA & LSTM

## 🚀 Overview
This project focuses on predicting stock prices using time series forecasting techniques. Both statistical and deep learning models are implemented and compared.

---

## 🔧 Models Used
- **ARIMA** (AutoRegressive Integrated Moving Average) – statistical model for linear patterns  
- **LSTM** (Long Short-Term Memory) – deep learning model for capturing nonlinear temporal dependencies  

---

## 📊 Features
- Time series preprocessing (ADF test, resampling)
- Handling non-stationarity
- ARIMA-based forecasting
- LSTM sequence modeling
- Model evaluation using RMSE and MAE
- 📅 10-day future stock price prediction

---

## 📈 Results
| Model | RMSE | MAE |
|------|------|-----|
| ARIMA | ~12 | ~9.6 |
| LSTM | ~1.2 | ~1.0 |

👉 LSTM significantly outperforms ARIMA in prediction accuracy.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib
- Statsmodels
- Scikit-learn
- TensorFlow / Keras

---

## 🧠 Key Insight
LSTM performs better than ARIMA for stock price prediction because it captures complex nonlinear patterns and long-term dependencies, while ARIMA struggles with non-stationary and volatile data.

---

## 🔮 Future Work
- Hyperparameter tuning (AutoARIMA)
- Use of technical indicators (RSI, MACD)
- Implementation of GRU / Bidirectional LSTM
- Incorporating external data (news, sentiment)

---

## 📌 Conclusion
This project demonstrates the effectiveness of deep learning models like LSTM over traditional statistical approaches for financial time series forecasting.
