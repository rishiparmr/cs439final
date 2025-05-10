# TSLA Stock Forecasting Project
## Authors: Rishi Parmar (rsp182) & Smriti Wadhwa (ssw97)

A short, self-contained workflow that loads historical Tesla price data, builds a forecasting model, and visualizes the model’s performance. The entire pipeline lives in a single Jupyter notebook, structured into four clear phases:

1. **Loading the data** – pulls raw OHLCV prices from Yahoo Finance and saves a clean CSV.
2. **Exploratory Data Analysis** - What is the relationship between sentiment and stock price?
3. **Creating the model** – pre-processes the series, trains an LSTM on closing prices, and saves fitted weights for future use.  
4. **Visualizing the results** – plots the true versus predicted prices for the most recent 90 days, alongside diagnostic charts.

