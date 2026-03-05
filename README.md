# Multimodal Stock Price Prediction using LSTM

## 📌 Overview
This project explores a fundamental-data-driven approach to stock return prediction by leveraging financial statement information. Financial statements such as income statements and balance sheets provide insights into a company's financial health, profitability, and stability. By combining these indicators with deep learning techniques, this study aims to improve the reliability of stock return predictions.

## 📊 Dataset
The dataset used in this study consists of **quarterly financial statement data** from companies listed in the **S&P SL20 Index**, which represents leading companies in the Sri Lankan stock market.

### Key Financial Indicators
The following financial metrics were used as model features:

- Earnings Per Share (EPS)
- Dividend Per Share
- Dividend Payout Ratio
- Return on Equity (ROE)
- Return on Assets (ROA)
- Debt-to-Equity Ratio
- Net Profit

These indicators are widely used in **fundamental analysis** by investors and financial analysts to evaluate company performance and guide investment strategies.

---

## 🤖 Model
To capture temporal relationships within financial data, this project uses a **Long Short-Term Memory (LSTM)** neural network.

LSTM is a type of **Recurrent Neural Network (RNN)** designed to learn patterns from sequential or time-series data, making it well-suited for financial forecasting tasks.

### Model Approach
The prediction process follows a **two-step approach**:

1. **Stock Price Prediction**  
   The LSTM model is trained using historical financial indicators to predict future stock prices.

2. **Stock Return Calculation**  
   The predicted stock prices are then used to compute expected stock returns.

---

## 🧠 Technologies Used
- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

---

## 📈 Expected Outcome
The model aims to demonstrate that **financial statement indicators can significantly contribute to stock return prediction**, providing investors with a **fundamental-data-driven forecasting approach** rather than relying solely on price trends.

---
