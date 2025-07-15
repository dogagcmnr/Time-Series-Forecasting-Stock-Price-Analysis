# 📈 Time Series Forecasting: Stock Price Analysis

## 🧠 Project Overview
This notebook demonstrates a complete time series forecasting workflow using 50 days of daily stock price data. The analysis includes trend visualization, technical indicators, stationarity testing, ARIMA modeling, and a 5-day price forecast with error evaluation and trend interpretation.

---

## 📁 Dataset Summary
- **Time Frame:** January – February 2023  
- **Records:** 50 daily stock entries  
- **Columns:** Date, Open, High, Low, Close, Volume

---

## 💡 What’s Included
- Time-based indexing and visualization  
- Technical indicators (SMA, EMA, RSI, MACD)  
- Stationarity checks using the ADF test  
- ARIMA(2,1,2) model fitting  
- 5-day forecast with MAE, MSE, RMSE  
- Trend-based investment suggestion

---

## 📐 Indicators Used
- **Simple Moving Average (SMA):** Average of past prices over a fixed window  
- **Exponential Moving Average (EMA):** Weighted average emphasizing recent data  
- **Relative Strength Index (RSI):** Measures recent price momentum to detect overbought/oversold zones  
- **MACD:** Combines EMAs to track trend direction and signal shifts

---

## 📊 Forecast Performance
- **Model:** ARIMA(2,1,2)  
- **Forecast Horizon:** 5 days  
- **MAE:** 0.3098  
- **MSE:** 0.1517  
- **RMSE:** 0.3896  
- **Expected Return (5-day):** +4.40%  
- **Investment Signal:** *BUY – Upward momentum expected*

---

## 📤 Output Example

| Date       | Predicted Price |
|------------|------------------|
| 2023-02-21 | $182.80          |
| 2023-02-22 | $184.81          |
| 2023-02-23 | $186.82          |
| 2023-02-24 | $188.83          |
| 2023-02-25 | $190.84          |

---

## 🔧 Tools & Libraries
- **Python**  
- `pandas`, `numpy` – Data processing  
- `matplotlib`, `seaborn` – Data visualization  
- `statsmodels` – ARIMA modeling, ADF test (`adfuller`)  
- `sklearn.metrics` – MAE, MSE, RMSE evaluation

---

## 🚀 How to Run
1. Clone the repository  
2. Install dependencies: `pip install -r requirements.txt`  
3. Open the notebook: `jupyter notebook time_series_analysis.ipynb`  
4. Follow section by section for analysis and forecasting

---

## 🧠 What I Learned
I learned how to combine ARIMA modeling with technical indicators to forecast short-term price trends, test model assumptions, and interpret the resulting direction using data-driven signals.

---

📬 For collaboration or feedback, feel free to reach out:  
📮 gocmenerdoga@gmail.com  
🌐 [Doğa Göçmener LinkedIn Profile](https://www.linkedin.com/in/dogagocmener/)  
