# **Momentum Trading Strategies on the Russian Stock Market**

### **Overview**

This project implements and evaluates momentum-based trading strategies in the Russian stock market. Specifically, we test:

*  A classical momentum strategy (**Buy Winners – Sell Losers**).
*  A technical indicator-based approach using the **Relative Strength Index (RSI)**.
*  Machine learning models, including **Random Forest** and **Support Vector Regression (SVR)**, trained on stock price time-series features.
  
Our analysis confirms the presence of momentum effects in the Russian stock market, which can be exploited through systematic trading strategies. Classical momentum-based strategies, such as RSI Momentum and Buy Winners - Sell Losers, provide strong foundations for leveraging these effects.

Machine learning models, despite using only simple and readily available time-series features, successfully outperformed the baseline benchmarks (risk-free rate and buy-and-hold strategy). However, they generally underperformed compared to classical momentum-based strategies. This suggests that while ML models capture market movements to some extent, they require further refinement to become competitive.

### **Files**

*  **Momentum_Trading_Strategies.pdf** – Detailed report explaining the methodology, data, and findings.
*  **Backtest_Momentum_Trading_Strategies.ipynb** – Jupyter Notebook containing the full implementation, backtesting results, and visualizations.
*  **risk_free_rates.csv** – Russian 3-month and 30-year zero-coupon government bond rates.
*  **dividends_splits.csv** – Corporate actions data for adjusted price calculations.
