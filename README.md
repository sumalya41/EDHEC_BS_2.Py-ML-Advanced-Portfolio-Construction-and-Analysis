Advanced Portfolio Construction and Analysis

By Prof. Vijay Vaidyanathan and Prof. Lionel Martellini
# 📊 EDHEC Portfolio Management & Risk Modeling with Python

Welcome to this repository! This project contains my notes, code implementations, and portfolio construction models developed during the **Investment Management with Python and Machine Learning** specialization by **EDHEC Business School** on Coursera. 

This repository specifically focuses on the portfolio theory and risk management modules taught by **Prof. Vijay Vaidyanathan** and **Prof. Lionel Martellini** (Courses: *Fundamentals of Portfolio and Risk Management* & *Meeting Investors' Goals*).

## 📖 Overview
The goal of this repository is to bridge the gap between advanced academic portfolio theory and practical quantitative finance using Python. It moves beyond basic Modern Portfolio Theory (MPT) to explore robust portfolio construction, risk budgeting, and alternative weighting schemes used by institutional asset managers today.

## 🧠 Key Financial Concepts Implemented
* **Modern Portfolio Theory (MPT):** Mean-Variance Optimization (MVO), Efficient Frontier, and the Capital Asset Pricing Model (CAPM).
* **Performance Measurement:** Sharpe Ratio, Sortino Ratio, Maximum Drawdown, and Value at Risk (VaR).
* **Advanced Portfolio Construction:**
  * **Global Minimum Variance (GMV) Portfolio**
  * **Maximum Diversification Portfolio**
  * **Risk Parity / Risk Budgeting:** Allocating capital based on risk contributions rather than dollar weights.
  * **Black-Litterman Model:** Combining market equilibrium with investor views to generate stable expected returns.
* **Monte Carlo Simulations:** Simulating asset returns and evaluating the statistical significance of portfolio performance.
* **Factor Investing:** Understanding systematic risk factors (Size, Value, Momentum) and their role in portfolio allocation.

## 💻 Technical Stack & Libraries
All financial models and optimizations are built from scratch using the Python data science ecosystem:
* **Data Manipulation:** `pandas`, `numpy`
* **Financial Data:** `yfinance` (for fetching historical stock/ETF data)
* **Mathematical Optimization:** `scipy.optimize` (for basic Mean-Variance), `cvxpy` (for advanced convex optimization and risk parity constraints)
* **Data Visualization:** `matplotlib`, `seaborn` (for plotting Efficient Frontiers and risk contribution charts)
* **Statistical Analysis:** `scipy.stats`

## 📂 Repository Structure
```text
├── data/                   # Historical price data (CSVs)
├── notebooks/              
│   ├── 01_returns_and_risk.ipynb       # Computing historical returns, volatility, and correlation matrices
│   ├── 02_efficient_frontier.ipynb     # Plotting the efficient frontier and finding the Tangency Portfolio
│   ├── 03_advanced_optimization.ipynb  # GMV, Max Diversification, and Risk Parity implementations
│   ├── 04_black_litterman.ipynb        # Implementing the Black-Litterman expected return model
│   └── 05_monte_carlo.ipynb            # Simulating future portfolio paths
├── src/                    # Reusable Python functions for portfolio optimization
├── requirements.txt        # Python dependencies
└── README.md
