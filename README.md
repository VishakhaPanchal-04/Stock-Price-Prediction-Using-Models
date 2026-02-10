STOCK PRICE PREDICTION USING MODELS

This repository contains a stock price prediction project that uses ARIMA and LSTM models to forecast future stock prices. 
The objective is to analyze historical stock trends and patterns and compare traditional statistical methods with deep learning techniques for improved prediction accuracy.

•TECH STACK :
Python,
Pandas,
NumPy,
ARIMA(statsmodels),
LSTM(TensorFlow/Keras),
Matplotlib

•Dataset :
Historical stock price data was sourced from Kaggle, including daily open, high, low, close prices, and trading volume.

•Methodology :
The stock price data was first cleaned and converted into a time-series format. ARIMA was applied to capture trends and seasonality, while an LSTM model was used to learn long-term and non-linear patterns. Both models were trained on historical data and tested on unseen data to compare their performance.

•Results :
The models were able to predict future stock price movements with reasonable accuracy. LSTM performed better in capturing complex patterns, while ARIMA provided stable results for trend-based forecasting.