
# Portfolio Optimization Project

This project implements a Monte Carlo simulation and optimization framework to construct an efficient investment portfolio from six high-cap U.S. stocks spanning diverse sectors (Tech, Healthcare, Financials, Energy, Industrials, Consumer Discretionary).

## Objective

The goal is to identify optimal portfolio weightings under different investor risk profiles by:

- Simulating 10,000 random portfolios
- Calculating expected return, volatility, and Sharpe ratio
- Finding the maximum Sharpe ratio, minimum volatility, and Capital Allocation Line (CAL) tangent portfolios
- Visualizing the efficient frontier

## Features

- Sector-diversified stock selection
- Log return calculations and risk-adjusted metrics
- Use of `scipy.optimize` to solve constrained portfolio optimization
- Visualizations: Return histograms, efficient frontier, CAL, and portfolio weightings

## Requirements

- Python 3.x
- `pandas`, `numpy`, `matplotlib`, `yfinance`, `scipy`

Install dependencies with:
```bash
pip install pandas numpy matplotlib yfinance scipy
