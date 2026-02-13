Your README is currently one long line and includes ::contentReference... at the end.
Replace the entire README with this:

# Stock Price Forecasting for Apollo Tyres Ltd. (Time Series)


This project analyzes historical stock price data and performs time series forecasting using classical methods.


## What’s included
- Data loading and cleaning
- Visual analysis of stock price trend
- Stationarity checks (ADF test)
- Forecasting using ARIMA / auto-ARIMA
- Model evaluation using error metrics


## Files
- `apollo_stock_forecasting.ipynb` — main notebook
- `CIA_3.csv` — dataset used by the notebook
- `requirements.txt` — dependencies


## How to run (Local)
1) Install dependencies
```bash
pip install -r requirements.txt

Start Jupyter

jupyter notebook

Open and run

apollo_stock_forecasting.ipynb

Notes

Keep CIA_3.csv in the same folder as the notebook (repo root), otherwise the notebook file path will break.
