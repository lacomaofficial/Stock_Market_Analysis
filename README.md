# Stock Market Technical Analysis Tool

## Overview
This Python tool provides functionality for analyzing stock market data and generating trading signals based on various technical indicators. It includes functions for calculating indicators such as Simple Moving Averages (SMA), Moving Average Convergence Divergence (MACD), Relative Strength Index (RSI), Bollinger Bands, and Stochastic Oscillator. Additionally, it allows for plotting trading signals and comparing short-term and long-term indicators.

### Stock Markey Analysis App
1. **Finding the Company Name**: To look up a company's name on Yahoo Finance, use this link: [Yahoo Finance Nikkei 225](https://finance.yahoo.com/quote/%5EN225/). For example, to find Nike's ticker, you would use ^N225.

2. **Interpreting the Charts**:
   - The **red line** on the chart represents the stock price.
   - The **blue line** indicates the buy signal.
   - **Rules for Buying or Selling**:
     - If the blue line rises to 4, it suggests you should buy the stock at 100%.
     - If the blue line falls below 0, it's a signal to sell the stock.

3. **Using the Signals**: This system is designed for medium and long-term investments. It combines mathematical functions and market signals in a simplified manner to aid in investment decisions.

4. **Additional Resources**: For more information, check out my project on stock market analysis here: [Stock Market Analysis on Hugging Face](https://huggingface.co/spaces/JayLacoma/Stock_Market_Analysis).


## Libraries Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computing.
- **yfinance**: For fetching historical market data.
- **Matplotlib**: For creating static plots.
- **Plotly**: For generating interactive plots.
- **Hugging Face Transformers**: For sentiment analysis.
- **Meta Prophet**: For time series forecasting and analyzing seasonality.

## Functions
- `calculate_sma`: Calculates Simple Moving Averages.
- `calculate_macd`: Calculates Moving Average Convergence Divergence.
- `calculate_rsi`: Calculates Relative Strength Index.
- `calculate_bollinger_bands`: Calculates Bollinger Bands.
- `calculate_stochastic_oscillator`: Calculates Stochastic Oscillator.
- `generate_trading_signals`: Generates trading signals based on various indicators.
- `plot_trading_signals`: Plots closing prices and combined trading signals.
- `plot_combined_signals`: Generates an interactive plot showing stock price and trading signals.
- `calculate_short_term_indicators`: Calculates short-term indicators including MACD, Average True Range (ATR), and On-Balance Volume (OBV).
- `compare_signals`: Compares short-term and long-term signals.

## Usage

### 1. Stock Market Data Retrieval

### 2. Generate Trading Signals

### 3. Visualize Trading Signals

### 4. Compare Short-term and Long-term Signals

### 5. Sentiment Analysis

### 6. Time Series Forecasting with Meta Prophet

![image](https://github.com/lacomaofficial/Stock_Market_Analysis/assets/132283879/30099265-7d96-4f46-aac3-6b13a211b350)

