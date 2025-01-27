# Wavelet-Based Financial Time Series Analysis

This repository contains code and a presentation on using wavelet transforms for financial time series analysis, specifically for stock market data. The project demonstrates how wavelet transforms can be used to generate buy and sell signals for stocks, providing insights into market trends and volatility.

## Files in the Repository

   - Contains Python code for downloading stock data, computing the Continuous Wavelet Transform (CWT), and generating buy/sell signals.
   - The code uses the Ricker wavelet to analyze stock price data and identifies optimal parameters for trading signals.
   - Includes backtesting functionality to evaluate the performance of the wavelet-based trading strategy.


## Key Features

- **Wavelet Transform for Financial Data**: The project demonstrates how wavelet transforms can capture both time and frequency variations in stock price data, making them ideal for analyzing non-stationary financial time series.
  
- **Buy/Sell Signal Generation**: The code generates buy and sell signals based on wavelet coefficients, allowing for the identification of potential trading opportunities.

- **Backtesting**: The repository includes a backtesting function to evaluate the performance of the wavelet-based trading strategy using historical stock data.

- **Hyperparameter Optimization**: The code explores different wavelet scales and thresholds to find the optimal parameters for generating trading signals.

