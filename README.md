# Wavelet-Based Financial Time Series Analysis

This repository contains code and a presentation on using wavelet transforms for financial time series analysis, specifically for stock market data. The project demonstrates how wavelet transforms can be used to generate buy and sell signals for stocks, providing insights into market trends and volatility.

## Files in the Repository

1. **`vertopal.com_Wavelet_Indicator.pdf`**
   - Contains Python code for downloading stock data, computing the Continuous Wavelet Transform (CWT), and generating buy/sell signals.
   - The code uses the Ricker wavelet to analyze stock price data and identifies optimal parameters for trading signals.
   - Includes backtesting functionality to evaluate the performance of the wavelet-based trading strategy.

2. **`Wavelets Presentation.pdf`**
   - A presentation that introduces wavelet transforms and their application in financial time series analysis.
   - Covers key concepts such as Fourier Transforms, Short-Time Fourier Transforms (STFT), Continuous Wavelet Transforms (CWT), and Discrete Wavelet Transforms (DWT).
   - Explains how wavelets can be used as market indicators and provides examples of buy/sell signals generated using wavelet transforms.

## Key Features

- **Wavelet Transform for Financial Data**: The project demonstrates how wavelet transforms can capture both time and frequency variations in stock price data, making them ideal for analyzing non-stationary financial time series.
  
- **Buy/Sell Signal Generation**: The code generates buy and sell signals based on wavelet coefficients, allowing for the identification of potential trading opportunities.

- **Backtesting**: The repository includes a backtesting function to evaluate the performance of the wavelet-based trading strategy using historical stock data.

- **Hyperparameter Optimization**: The code explores different wavelet scales and thresholds to find the optimal parameters for generating trading signals.

## Requirements

To run the code, you will need the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `yfinance`
- `scipy`

You can install these libraries using pip:

```bash
pip install numpy pandas matplotlib yfinance scipy
