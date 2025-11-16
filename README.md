# Quant Stock Analysis

This project explores basic quantitative trading ideas using Python, pandas, and NumPy — all built and tested in Google Colab.

## Overview
- Downloaded Apple (AAPL) & Telsa (TSLA) stock data using `yfinance`
- Calculated 20-day moving average and daily returns
- Visualized results using `matplotlib`
- Downloaded Nvidia (NVDA) stock data using yfinance
- Calculated 20-day moving average and volitility of the past 10 years of NVDA stock
- Visulaized results using matplotlib

## Project Structure
quant-stock-analysis/

- notebooks/
  - aapl_analysis.ipynb          # Apple moving average & daily return analysis
  - tsla_analysis.ipynb          # Tesla moving average and return comparison
  - nvda_volatility.ipynb        # Nvidia 10-year volatility and trend study

- results/
  - aapl_moving_average.png      # Saved chart for Apple
  - tsla_moving_average.png      # Saved chart for Tesla
  - nvda_volatility.png          # Saved chart for Nvidia
 
- requirements.txt 
  - numpy
  - pandas
  - yfinance
  - matplotlib
  - os
