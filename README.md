# 📊 Trading Strategy Backtesting – SMA, SL/TP, Buy & Hold

This project builds a simple and clear backtesting tool for comparing different trading strategies on historical stock data using Python.

---

## 🚀 What It Does

- Fetches historical stock data using [`yfinance`](https://github.com/ranaroussi/yfinance)
- Implements and compares multiple strategies:
  - ✅ **SMA Crossover**
  - ✅ **Stop Loss / Take Profit (SL/TP)**
  - ✅ **Buy & Hold**
  - ⚙️ Optional logic for **option-based hedging**
- Simulates trades, tracks capital over time, and visualizes the results

---

## 📈 Metrics Evaluated

- **CAGR (Compound Annual Growth Rate)**
- **Max Drawdown**
- **Sharpe Ratio**
- **Sortino Ratio**
- **Win Rate**
- **Average Holding Period**

---

## 📂 Files

- `backtest.ipynb` – Jupyter notebook with all the logic
- Modular functions for signal generation, trade simulation, and performance analysis

---

## 📦 Requirements

Install dependencies using pip:

```bash
pip install yfinance pandas matplotlib

