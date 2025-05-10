"""# TSLA Stock Forecasting Project

A short, self-contained workflow that loads historical Tesla price data, builds a forecasting model, and visualizes the model’s performance. The entire pipeline lives in a single Jupyter notebook, structured into three clear phases:

1. **Loading the data** – pulls raw OHLCV prices from Yahoo Finance and saves a clean CSV.  
2. **Creating the model** – pre-processes the series, trains an LSTM on closing prices, and saves fitted weights for future use.  
3. **Visualizing the results** – plots the true versus predicted prices for the most recent 90 days, alongside diagnostic charts.

---

## Folder layout

```text
├── notebook.ipynb        # Main analysis notebook (clean, readable, and modular)
├── tsla_ohlcv.csv        # Cached daily OHLCV data
├── README.md             # You are here
└── requirements.txt      # Exact package versions (optional, auto-generated)
