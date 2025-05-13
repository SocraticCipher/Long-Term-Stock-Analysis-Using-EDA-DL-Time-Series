# Long-Term-Stock-Analysis-Using-EDA-DL-Time-Series

---

## 📊 Project Objectives

- Visualize long-term trends in stock prices
- Analyze daily volatility through high-low price differences
- Evaluate trading volume impact on prices
- Use moving averages (20-day, 50-day, 200-day) to detect trends
- Prepare data for time series modeling or deep learning applications

---

## 📁 Dataset Overview

- **Source**: Likely fetched from Yahoo Finance or similar APIs
- **Period Covered**: 15 years of daily stock data
- **Typical Columns**:
  - `Date`
  - `Open`
  - `High`
  - `Low`
  - `Close`
  - `Volume`
  - `Adj Close` (if applicable)

---

## 🧪 Exploratory Data Analysis (EDA)

The notebook includes:

### 1. **Price Trend Over Time**
   - Line plots for `Close` price evolution
   - Insights into bull and bear phases

### 2. **Daily High-Low Volatility**
   - Daily volatility = `High - Low`
   - Volatility trend and distribution

### 3. **Moving Averages**
   - Computation and visualization of:
     - 20-day MA (short-term trends)
     - 50-day MA (medium-term trends)
     - 200-day MA (long-term trends)
   - Crossovers and momentum interpretation

### 4. **Volume vs. Price**
   - Scatter plots and volume bars
   - Correlation between price movements and traded volume

---

## 🤖 Time Series Modeling 

If the notebook includes modeling:

- Use of RNNs, LSTM, or other deep learning models
- Preprocessing: Normalization, sequence generation
- Train-test split strategy
- Model evaluation (MSE, RMSE, etc.)
- Forecast visualization

---

## 📷 Visualizations

- Time-series line plots
- Rolling window analyses
- Heatmaps 
- Candlestick charts 

---
