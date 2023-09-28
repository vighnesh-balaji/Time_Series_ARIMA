# Time_Series_ARIMA
Predicting monthly champagne sales by leveraging ARIMA and SARIMAX


## Time Series Project Overview

- Created a tool to predict champagne sales by finding out the seasons and trends in data
- Performed cleaning to make data usable
- Checked for stationarity using adfuller hypothesis testing.
- Plotted the ACF and PACF plots to estimate parameters p,d,q


## Code and Resources Used 

Python Version - 3.9 Packages: pandas, numpy, matplotlib, statsmodel

## Initial Steps

- Renamed the columns of the dataframe
- Changed the datatype of the month column and made it as the index
- Built a function to calculate adfuller test

## Differencing 

- Found out the seasonal difference by performing 12 shifts in data
- Used this to test for stationarity
- Plotted ACF and PACF plots
- Found out lags, autoregressive terms, and non-seasonal differences (p,q,d)
- the same approach using SARIMAX gives us a closer match to the original data
- Predicted for the next 24 months

![download](https://github.com/vighnesh-balaji/Time_Series_ARIMA/assets/39007695/1e40da8b-1f6b-4d1a-b268-94f546630cce)

  
