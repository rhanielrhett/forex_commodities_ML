# XAUUSD Historical Chart Data Analysis

## 1. Source of the Data

The dataset used in this project is sourced from [https://www.investing.com/currencies/xau-usd-historical-data]. The data consists of historical price information for the XAUUSD currency pair, representing the value of gold (XAU) priced in US dollars (USD) over a specified time period on a daily chart. Historical data coverage is from 2010 to 2023.

The dataset file comes in a CSV format: XAU_USD_Historical_Data.csv

## 2. Description and Metadata

The dataset includes the following columns:

- **Date**: The date of the recorded price.
- **Price**: The price of the XAUUSD pair for the Date
- **Open**: The opening price of XAUUSD on that date.
- **High**: The highest price of XAUUSD on that date.
- **Low**: The lowest price of XAUUSD on that date.
- **Close**: The closing price of XAUUSD on that date.
- **Volume**: The trading volume of XAUUSD on that date. This is empty in the raw dataset but this can be computed from the open, high, low, close
- **Change%: The percentage change of the price relative from the previous day

This dataset covers historical price data, which can be used for various analysis and modeling purposes in the field of financial data analysis, time series forecasting, and algorithmic trading strategies.

## 3. Use Case

### Financial Trend Analysis
This dataset can be utilized to analyze historical trends in the price of gold against the US dollar. By visualizing the data and applying statistical techniques, insights can be gained into the long-term trends, seasonal patterns, and volatility of the XAUUSD currency pair.

### Trading Strategy Development
Traders and investors can use this dataset to develop and backtest trading strategies based on technical indicators and machine learning models. Strategies may include trend-following, mean-reversion, or volatility-based approaches to capitalize on price movements in the XAUUSD market.

### Economic Analysis
The price of gold often reflects macroeconomic factors such as inflation, geopolitical events, and monetary policy decisions. Analysts can leverage this dataset to study the relationship between gold prices and economic indicators, providing insights into the broader economic landscape.

## 4. Other Data
There might be more relevant data which can be used as auxiliary dataset depending on the use case. Feel free to use any.
