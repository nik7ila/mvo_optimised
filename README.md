# mvo_optimised
Executive Summary

This project applies MVO to optimize portfolio weights across selected assets from 2015–2025. The resulting portfolio outperforms an equal-weighted benchmark in terms of return and risk-adjusted metrics like the Sharpe Ratio. These insights are directly applicable in investment consulting, quant research, and fintech analytics—fields where data-driven allocation decisions add measurable value for clients and institutions.

# 📊 Mean-Variance Optimization (MVO) Portfolio

This project implements a portfolio optimization strategy using the Markowitz Mean-Variance framework. It selects asset weights that maximize the Sharpe Ratio while minimizing portfolio volatility.

## 🧠 Key Concepts
- Modern Portfolio Theory (Markowitz)
- Mean-Variance Optimization
- Efficient Frontier
- Sharpe Ratio Maximization

## 📁 Contents
- Stock data collection via `yfinance`
- Log returns and risk metrics
- Optimization using `scipy.optimize`
- Efficient Frontier plot
- Comparison of equal-weighted vs optimized portfolio performance

## 📈 Visualizations
- Efficient frontier curve with optimal portfolio
- Cumulative returns: Equal-weighted vs MVO portfolio

## 📎 Dependencies
```bash
pip install yfinance numpy pandas matplotlib scipy
