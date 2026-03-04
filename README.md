# 📊 Historical and Forecast Analysis of Stocks (2014–2024)

---

## 🎯 Project Objective

This project aims to perform a quantitative and statistical analysis of a set of US stocks over the period **2014–2024**, including:

- Historical performance analysis
- Cumulative returns and CAGR calculation
- Return distribution analysis
- Stationarity testing
- Modeling and forecasting with **ARIMA**
- Performance evaluation using error metrics

---

## 📈 Analyzed Stocks

The selected stocks belong to different industrial sectors:

- **(TSLA)** – Automotive / EV
- **(GM)** – Automotive
- **(LMT)** – Defense / Aerospace
- **(BA)** – Aerospace
- **(GIS)** – Consumer Goods
- **(HRL)** – Food

---

## 🛠 Libraries Used

The project is developed in **Python** using the following libraries:

- `yfinance` – Financial Data Download
- `pandas` – Data Manipulation
- `numpy` – Numerical Computing
- `matplotlib`, `seaborn` – Data Visualization
- `scipy.stats` – Statistical Analysis
- `statsmodels` – ARIMA, ADF Test
- `sklearn` – Error Metrics
- `ffn` – Advanced Financial Analysis
- `warnings` – Warning Management

---

## 📥 Data Download

Historical data is downloaded via `yfinance` for the period:

May 31 2014 – May 31 2024

The closing prices ('Close') for each stock are analyzed.

---

## 📊 Analyses Performed

### 1️⃣ Viewing Historical Performance

- Closing Price Chart
- Direct Stock Comparison

---

### 2️⃣ Calculating Returns

For each stock, the following are calculated:

- **Cumulative Return**
- **CAGR (Compound Annual Growth Rate)**

---

### 3️⃣ Cumulative Return Analysis

- Construction of the Cumulative Return Chart
- Comparison of Growth Over Time
- Relative Volatility Analysis

---

### 4️⃣ Statistical Analysis of Returns

- Distribution of Returns
- Study of Normality
- Key Statistical Indicators:
- Mean
- Standard Deviation
- Skewness
- Kurtosis

---

### 5️⃣ Stationarity Test (ADF Test)

To test the stationarity of time series, the following is used:

- **Augmented Dickey-Fuller Test**

Objective:
- Determine whether the series is stationary
- Establish the need for differencing for the ARIMA model

---

### 6️⃣ ARIMA Modeling

For each security:

- Identify the appropriate ARIMA model
- Train the model
- Generate future forecasts

ARIMA Components:
- **AR (AutoRegressive)**
- **I (Integrated)**
- **MA (Moving Average)**

---

### 7️⃣ Model Evaluation

Performance Predictive performance is evaluated through:

- **MAE (Mean Absolute Error)**

Comparison between:
- Actual values
- Predicted values

---

## 📌 Notebook Structure

1. Import libraries
2. Download data
3. Graphical price analysis
4. Return calculation
5. Statistical analysis
6. ADF test
7. ARIMA modeling
8. Forecast evaluation

---

## 🚀 Possible Extensions

- Construction of an optimized portfolio
- Risk-return analysis (Sharpe Ratio)
- Strategy backtesting
- Comparison with benchmarks (e.g., S&P 500)
- Implementation of GARCH models for volatility

---

## 🧠 Applied Skills

- Time Series Analysis
- Financial econometrics
- Predictive modeling
- Data visualization
- Statistical model evaluation

---

## ▶️ How to Run the Project

1. Install the dependencies:

```bash
pip install yfinance pandas numpy matplotlib seaborn scipy statsmodels scikit-learn ffn
```

2. Open the Jupyter notebook:

```bash
jupyter notebook
```

3. Run the cells in sequential order.








