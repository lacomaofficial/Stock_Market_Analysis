## Stock Market Technical Analysis Tool

### Overview
This Python tool provides functionality for analyzing stock market data and generating trading signals based on various technical indicators. It includes functions for calculating indicators such as Simple Moving Averages (SMA), Moving Average Convergence Divergence (MACD), Relative Strength Index (RSI), Bollinger Bands, and Stochastic Oscillator. Additionally, it allows for plotting trading signals and comparing short-term and long-term indicators.

### Libraries Used
- Pandas: For data manipulation and analysis.
- NumPy: For numerical computing.
- yfinance: For fetching historical market data.
- Matplotlib: For creating static plots.
- Plotly: For generating interactive plots.

### Functions
1. **calculate_sma**: Calculates Simple Moving Averages.
2. **calculate_macd**: Calculates Moving Average Convergence Divergence.
3. **calculate_rsi**: Calculates Relative Strength Index.
4. **calculate_bollinger_bands**: Calculates Bollinger Bands.
5. **calculate_stochastic_oscillator**: Calculates Stochastic Oscillator.
6. **generate_trading_signals**: Generates trading signals based on various indicators.
7. **plot_trading_signals**: Plots closing prices and combined trading signals.
8. **plot_combined_signals**: Generates an interactive plot showing stock price and trading signals.
9. **calculate_short_term_indicators**: Calculates short-term indicators including MACD, Average True Range (ATR), and On-Balance Volume (OBV).
10. **compare_signals**: Compares short-term and long-term signals.

### Usage
1. **Stock Market Data Retrieval**: Download historical market data using the `yfinance` library.
2. **Generate Trading Signals**: Utilize the `generate_trading_signals` function to compute trading signals based on selected indicators.
3. **Visualize Trading Signals**: Plot trading signals using `plot_trading_signals` and `plot_combined_signals` functions.
4. **Compare Short-term and Long-term Signals**: Use `calculate_short_term_indicators` to compute short-term indicators and `compare_signals` to visualize the comparison.

### Example
```python
ticker = 'NVDA'
df = yf.download(ticker, start='2022-01-01', end='2025-01-01')

generate_trading_signals(df)
plot_trading_signals(df.tail(60))
plot_combined_signals(df.tail(20))
df_term = calculate_short_term_indicators(df)
compare_signals(df_term.tail(10))
```

