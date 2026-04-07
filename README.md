Stock Market Data Analysis by Decade (1970–2018)
Project Overview

This project analyzes historical stock market data spanning multiple decades to understand how stock prices and trading volumes evolved over time. The analysis focuses on data cleaning, time-series preparation, decade-based segmentation, and exploratory data analysis (EDA).

The objective is to identify long-term trends, volatility patterns, and structural changes in financial markets.

Research Questions
How have stock prices evolved across decades?
How has trading volume changed over time?
Are there structural differences between decades?
What long-term patterns emerge from historical stock data?
Dataset

This project uses historical stock market data containing:

Date
Open
High
Low
Close
Volume
Adjusted Close

Files used:

historical_stock_prices.csv
historical_stocks.csv

Place both files inside the data/ folder before running the notebook.

Data Cleaning

The following preprocessing steps were performed:

Converted Date column to datetime format
Removed duplicate entries
Handled missing values
Sorted dataset chronologically
Created decade-based segmentation
Exploratory Data Analysis

The analysis includes:

Time-series visualization of closing prices
Volume distribution analysis
Boxplots by decade
Summary statistics comparison
Decade-based segmentation
Key Findings
Stock prices show a long-term upward trend across decades
Trading volume increases significantly in later decades
Market volatility increases after 1990
Price outliers become more frequent in modern markets
Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Skills Demonstrated
Data Cleaning
Exploratory Data Analysis
Time Series Analysis
Data Merging
Financial Data Analysis
Data Visualization
