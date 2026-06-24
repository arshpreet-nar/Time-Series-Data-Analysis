# Time Series Data Analysis

This repository contains the deliverables for **Edutech Solution Data Analytics Internship - Task 10: Time Series Data Analysis**.

## Task Objective

Analyze stock market time series data using Python, Pandas, and Statsmodels. The analysis covers:

- Loading and cleaning the full stock market dataset
- Combining all stock and ETF CSV files
- Creating an aggregate market time series
- Visualizing price movement over time
- Calculating moving averages
- Checking stationarity with the Augmented Dickey-Fuller test
- Identifying trend and seasonality using seasonal decomposition
- Building a forecasting model
- Saving a forecasting plot

## Dataset

The notebook uses the whole dataset in the `DATA` folder:

- `DATA/stocks/*.csv`
- `DATA/etfs/*.csv`

The combined dataset includes each row's date, adjusted close, volume, symbol, and asset type.

## Required Deliverables

- `notebooks/time_series_stock_analysis.ipynb` - Time Series Analysis notebook using the whole dataset
- `outputs` - Forecasting plot for the aggregate market series
- `requirements.txt` - Python dependencies
- `scripts/generate_deliverables.py` - Script used to regenerate the notebook and plot

## How To Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open and run the notebook:

```bash
jupyter notebook notebooks/time_series_stock_analysis.ipynb
```

The notebook generates the forecasting plot at:

`outputs/whole_dataset_forecast.png`
