 stock-price-prediction-lstm
This project predicts stock prices using historical market data, statistical features, and an LSTM deep learning model. It includes data collection with yfinance, feature engineering, sequence preparation, model training, and evaluation to forecast future stock trends accurately.
 Stock Price Prediction using LSTM  
Predicting stock market closing prices using a Long Short-Term Memory (LSTM) neural network.

 Project Overview  
This project builds a deep learning model using **LSTM** to forecast stock prices based on historical OHLCV data and engineered features such as:

- Moving Averages (MA5, MA20)
- Volatility (STD20)
- Momentum
- Log returns
- Volume

The notebook performs **data preprocessing**, **feature engineering**, **sequence generation**, **model training**, **evaluation**, and **visualization**.
Model Architecture  
- **LSTM Layer (64 units, return_sequences=True)**
- **Dropout (0.2)**
- **LSTM Layer (32 units)**
- **Dropout (0.2)**
- **Dense Layer (1 neuron for prediction)**  
- **Optimizer:** Adam  
- **Loss:** MSE  

Sequence Length: **60** days  
Train/Test Split: **80/20**
## 🗂 Repository Structure

