# ASX Top 10 Stocks Analysis

## Overview

This project analyzes the 10 largest companies listed on the Australian Stock Exchange (ASX) by market capitalization. The dataset consists of end-of-day stock prices from July 1, 2022, to June 30, 2024, adjusted to exclude the impact of corporate events like dividend payments.

## Features

Stock Price Data Processing: Cleans and structures historical price data.

Statistical Analysis: Computes performance metrics of ASX's top 10 stocks.

Optimization Techniques: Uses scipy.optimize for portfolio optimization.

Data Visualization: Generates stock performance plots using matplotlib.

## Usage

To run this notebook:

Open the Jupyter Notebook and execute each cell sequentially.

## Expected Output 

### Stock Performance Metrics

- The mean returns provide insight into the average profitability of the ASX stocks, while the standard deviation measures their volatility.

- Stocks with higher mean returns and moderate volatility are considered favorable for investment.

### Covariance Matrix Interpretation

- The covariance matrix highlights the relationship between different stocks.

- A high positive covariance means two stocks tend to move in the same direction, reducing diversification benefits.

- A low or negative covariance suggests diversification potential, reducing overall portfolio risk.

### Optimal Portfolio Allocation

- The optimal weights indicate how much investment should be allocated to each stock for an optimized risk-return tradeoff.

- Stocks with higher allocations are expected to contribute positively to portfolio returns, while low or negative weights suggest they may not be beneficial in a risk-managed portfolio.

### Portfolio Risk and Return Analysis

- The portfolio return and variance help determine the expected gains and associated risks.

- A low standard deviation means a more stable investment, while a higher return with moderate risk is preferred for an optimized portfolio.





