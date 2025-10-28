# SMA Crossover Strategy Optimization with Backtrader

A beginner quantitative trading project built with **Python** and **Backtrader**, designed to test and evaluate **SMA crossover strategies** across different parameter combinations.  
The project includes **performance analytics** (Sharpe, Sortino, Return, Volatility, Winrate) and **3D visualizations** of the strategy metrics.

---

## Overview

This project evaluates a **Simple Moving Average (SMA)** crossover trading strategy by sweeping combinations of `fast` and `slow` SMA periods.  
Each combination is backtested using Backtrader, with key performance metrics collected for comparison.

The script outputs:
- Portfolio value curve over time 
- Sharpe, Sortino, Return, Volatility, and Winrate metrics   
- 3D plots for Sharpe ratio visualization   

---

## Features

Parameter optimization across multiple SMA combinations  
Performance analyzers (Sharpe, Sortino, Volatility, Returns, Winrate)  
Portfolio growth visualization  
3D visualization for Sharpe ratio and return-volatility relationship  
Simple, reproducible setup with Backtrader

---

## Requirements

- Python 3.9+
- Backtrader
- pandas
- numpy
- matplotlib
- yfinance 
- mpl_toolkits (for 3D visualization)
