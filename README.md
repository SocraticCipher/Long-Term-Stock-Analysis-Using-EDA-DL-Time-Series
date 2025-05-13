# 📈 Big Tech Stock Market Analysis (2010 - 2025)

This project presents an end-to-end exploratory analysis and predictive modeling of the historical stock prices of five leading technology companies:

- **Apple (AAPL)**
- **Amazon (AMZN)**
- **Google (GOOGL)**
- **Microsoft (MSFT)**
- **NVIDIA (NVDA)**

The analysis spans a 15-year period from **January 1, 2010** to **January 1, 2025**, and uses a mix of classical and deep learning-based time series forecasting models.

---

## 📦 Dataset Overview

The dataset includes **daily stock data** for each of the five companies with the following key features:

- `Open`, `High`, `Low`, `Close` prices
- `Volume` of shares traded
- Time period: **2010-01-01 to 2025-01-01**
- Combined into a multi-stock format for correlation and multivariate modeling

---

## 🎯 Objectives

- ✅ Perform **Exploratory Data Analysis (EDA)** to uncover market structure and historical patterns
- 📊 Visualize trends, volatility, volume shifts, and returns
- 🔁 Investigate **inter-stock correlations** (e.g., AAPL vs MSFT)
- 📈 Build and evaluate predictive models for future price trends using:
  - **ARIMA / SARIMAX** – Classical time series modeling
  - **Facebook Prophet** – Additive model with seasonality and trend components
  - **LSTM / Transformer** – Deep learning models for sequence prediction
  - **Multivariate Regression** – Predict one company’s stock based on others

---

## 📚 Libraries & Tools Used

| Category              | Libraries                                           |
|-----------------------|-----------------------------------------------------|
| Data Processing       | `numpy`, `pandas`                                   |
| Visualization         | `matplotlib`, `seaborn`, `plotly`                   |
| Statistical Modeling  | `statsmodels`, `pmdarima`                           |
| Forecasting Models    | `prophet`, `ARIMA`, `SARIMAX`                       |
| Deep Learning         | `tensorflow`, `keras`                               |
| Machine Learning      | `scikit-learn`                                      |

---

## 📈 Exploratory Data Analysis (EDA)

The notebook contains the following analyses:

- **Price Trend Over Time**  
  Visual comparisons of stock closing prices across the 15-year period.

- **Daily Volatility**  
  Based on high-low price differences to detect market activity surges.

- **Moving Averages**  
  Includes 20-day, 50-day, and 200-day moving averages to identify trends and crossovers.

- **Volume vs Price Relationships**  
  Scatter and line plots to assess whether trading volume leads or follows price movement.

- **Stock Returns & Distributions**  
  Daily percentage change analysis and histograms of returns.

- **Correlation Heatmaps**  
  To assess relationships among companies over time.

---

## 🤖 Modeling Techniques

This notebook explores a variety of forecasting models:

### 🔢 Classical Time Series
- **ARIMA / SARIMAX**: Autoregressive modeling with trend and seasonal decomposition
- **ACF/PACF** plots: To determine appropriate lags

### 📅 Prophet by Meta
- Automatically detects trends, seasonality, and changepoints
- Easy interpretability and modular forecasting

### 🧠 Deep Learning
- **LSTM (Long Short-Term Memory)**:
  - Handles sequences and memory in financial data
  - Trained on historical windowed prices
- **Transformer-based Models**:
  - Experimental section to test more advanced architectures for time series

### 📊 Multivariate Regression
- Predict the stock of one company (e.g., AAPL) using others (e.g., MSFT, NVDA) as features

---

## 📂 Project Structure

