# Australian Bank Stock Data Analysis

A beginner Python project exploring historical stock prices for four major Australian banks using Yahoo Finance data.

This was one of my first projects working with financial data in Python and using GitHub to share code.

## Overview

The Jupyter notebook downloads and explores historical price data for:

- Commonwealth Bank of Australia (`CBA.AX`)
- National Australia Bank (`NAB.AX`)
- Westpac Banking Corporation (`WBC.AX`)
- Australia and New Zealand Banking Group (`ANZ.AX`)

It retrieves roughly 5,000 calendar days of daily stock data, extracts closing prices, summarizes observations from the most recent 100 calendar days, and plots the closing-price histories.

## Tools

- Python
- pandas — data handling and descriptive statistics
- yfinance — Yahoo Finance market data
- matplotlib — charting through pandas
- Jupyter Notebook — interactive analysis

## How to run

1. Clone or download this repository.
2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open `stockData101.ipynb` in Jupyter Notebook or VS Code and run the cells in order.

The notebook also includes package-install commands in its first cell. A network connection is needed to retrieve current data from Yahoo Finance.

## Notes

- The date range is calculated relative to when the notebook runs, so results will change over time.
- The chart compares **raw closing prices**, not normalized returns or investment performance.
- The notebook is an introductory data exploration rather than a trading strategy or investment recommendation.
