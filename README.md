# 📈 Time Series Forecasting for Portfolio Management Optimization  

## 🚀 Project Overview  
This repository contains the implementation of **time series forecasting models** to optimize portfolio management strategies. The goal is to analyze historical financial data, predict future trends, and make data-driven investment decisions to maximize returns while minimizing risk.  

## 📊 Project Workflow  
1. **Data Collection & Preprocessing**  
   - Fetch historical stock data (2015-2025) using YFinance  
   - Clean, normalize, and handle missing values  
   - Perform **Exploratory Data Analysis (EDA)** and visualize trends  

2. **Time Series Forecasting**  
   - Build and compare forecasting models: **ARIMA, SARIMA, LSTM**  
   - Evaluate models using **MAE, RMSE, MAPE**  
   - Generate future price predictions for **TSLA, BND, SPY**  

3. **Portfolio Optimization**  
   - Compute **annual returns & volatility**  
   - Calculate **Sharpe Ratio & Value at Risk (VaR)**  
   - Optimize asset allocation based on forecasted trends  

4. **Final Analysis & Insights**  
   - Summarize portfolio performance based on predictions  
   - Adjust investment strategy for risk-return tradeoff  
   - Visualize cumulative returns & risk assessment  

## 📂 Project Structure  
```
📁 time-series-forecasting-portfolio-optimization  
│── 📂 data               # Raw and processed financial data  
│── 📂 notebooks          # Jupyter notebooks for EDA, modeling & forecasting  
│── 📂 src                # Python scripts for data processing & model training  
│── 📂 reports            # Analysis, insights & portfolio recommendations  
│── README.md            # Project documentation  
│── requirements.txt     # Required Python libraries  
│── main.py              # Main script to run forecasting & optimization  
```

## 🔧 Setup Instructions  
1. Clone this repository  
   ```bash
   git clone https://github.com/Elelanfik/time-series-forecasting-portfolio-optimization.git  
   cd time-series-forecasting-portfolio-optimization
   ```  
2. Create a virtual environment & install dependencies  
   ```bash
   python3 -m venv venv  
   source venv/bin/activate  # On Windows: venv\Scripts\activate  
   pip install -r requirements.txt  
   ```  
3. Run the forecasting & portfolio optimization script  
   ```bash
   python main.py  
   ```  

## 🛠 Tools & Technologies  
- **Python** – Core programming language  
- **YFinance** – Fetching real-time stock data  
- **Pandas & NumPy** – Data processing & manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **Statsmodels** – ARIMA & SARIMA models  
- **TensorFlow/Keras** – LSTM model implementation  
- **Scipy & CVXPY** – Portfolio optimization  

## 📜 License  
This project is open-source and available under the **MIT License**.  
