# 🧠 Stock Market Movement Prediction using Random Forest

This project applies **Random Forest Classification** to predict **next-day stock price movement (Up/Down)** using historical stock data and technical indicators.

---

### ⚙️ Project Overview
- Collected daily stock data using **Yahoo Finance API (`yfinance`)**
- Engineered key indicators: Moving Averages, RSI, and Momentum  
- Built a **RandomForestClassifier** to predict whether the stock price will increase the next day  
- Evaluated using Accuracy, Precision, Recall, and ROC-AUC  

---

### 📊 Results
| Metric | Score |
|---------|--------|
| Accuracy | 73% |
| ROC-AUC | 0.80 |
| Important Features | MA5, RSI, Momentum |

---

### 🛠️ Tools Used
Python · Pandas · NumPy · scikit-learn · Matplotlib · yfinance

---

### 🚀 How to Run
1. Clone this repo:  
   ```bash
   git clone https://github.com/your-username/StockMovementPrediction_RF.git
