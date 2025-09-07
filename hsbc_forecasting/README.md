# HSBC — Financial Forecasting & Risk Analysis (2019–2024)

**Business question**: Can we improve short-term trend forecasting accuracy and identify volatility periods to inform risk-adjusted strategies?

## Methods
- Time-series modelling: ETS/Exponential Smoothing, Regression, Random Forest (for features)
- Evaluation: MAE/MAPE; volatility flags
- Visualisations with Matplotlib

## Result (from report)
- Achieved **~10–15% improvement** in short-term trend prediction accuracy; highlighted volatility periods for strategy.

## How to run
- Install requirements, then run `notebooks/forecasting.ipynb`.
- Optionally use `yfinance` to fetch OHLC data (no raw data included).

## Files
- `notebooks/` — modelling & evaluation
- `images/` — charts for README
- `data/` — excluded raw; include small processed samples if needed
