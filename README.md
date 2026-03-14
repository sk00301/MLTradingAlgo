# 📈 ML Trading Algorithm

An unsupervised machine learning-based **algorithmic trading strategy** that clusters stocks using technical indicators and constructs data-driven portfolios from the results.

---

## 📌 Overview

This project applies unsupervised ML techniques to identify patterns and group stocks based on their market behavior — without relying on labeled data. The goal is to design a systematic trading strategy by leveraging clustering algorithms on key financial indicators, then selecting and weighting assets based on the resulting structure.

---

## 📁 Repository Structure

```
MLTradingAlgo/
└── Unsupervised_Machine_Learning_trading_algo.ipynb   # Full pipeline: data → features → clustering → strategy
```

---

## 🔄 Workflow

```
Fetch Stock / Market Data
        │
        ▼
Feature Engineering
(Technical Indicators: RSI, MACD, Bollinger Bands, etc.)
        │
        ▼
Unsupervised Clustering
(K-Means or similar)
        │
        ▼
Portfolio Construction
(Select stocks from target clusters)
        │
        ▼
Backtesting & Performance Evaluation
```

---

## 🧰 Tech Stack

- **Language:** Python 3
- **Environment:** Jupyter Notebook
- **Libraries:**
  - `pandas`, `numpy` — data manipulation
  - `scikit-learn` — clustering (K-Means, etc.)
  - `yfinance` / `pandas_datareader` — market data fetching
  - `matplotlib`, `seaborn` — visualization and performance plots
  - `scipy` / `PyPortfolioOpt` *(if applicable)* — portfolio optimization

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sk00301/MLTradingAlgo.git
cd MLTradingAlgo
```

### 2. Install dependencies

```bash
pip install numpy pandas scikit-learn yfinance matplotlib seaborn scipy
```

### 3. Run the notebook

Open and run all cells in:

```
Unsupervised_Machine_Learning_trading_algo.ipynb
```

> ⚠️ An active internet connection is required to fetch live/historical market data.

---

## 🧠 Key Concepts

**Unsupervised Learning for Trading** — unlike supervised approaches, no explicit buy/sell labels are used. Instead, clustering reveals natural groupings in the data, which are then used to form trading signals.

**Technical Indicators** — features like RSI (momentum), MACD (trend), and Bollinger Bands (volatility) are computed per asset and used as inputs to the clustering model.

**Portfolio Construction** — stocks from a selected cluster (e.g., high-momentum or low-volatility group) are combined into a portfolio, optionally weighted using optimization techniques.

---

## ⚠️ Disclaimer

This project is for **educational and research purposes only**. It does not constitute financial advice. Past backtested performance is not indicative of future results. Always do your own research before making any investment decisions.

---

## 📄 License

This project is open source. Feel free to use and build upon it.

---

## 🙋 Author

**[sk00301](https://github.com/sk00301)**
