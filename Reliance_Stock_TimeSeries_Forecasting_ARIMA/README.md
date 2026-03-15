# Reliance Stock Time Series Forecasting using ARIMA

## Project Overview

This project performs financial time series analysis on Reliance Industries Ltd. stock prices using ARIMA models in R.

The objective is to analyze historical stock behavior and generate short-term forecasts using statistical modeling techniques.

## Dataset

Daily closing price data for Reliance Industries Ltd. obtained from Yahoo Finance.

Time period analyzed:
2012 – 2025

## Methodology

Data Collection
Historical stock prices downloaded using the quantmod package.

Stationarity Testing
ADF Test and KPSS Test were used to determine stationarity.

Data Transformation
Log transformation and differencing were applied to convert prices into stationary returns.

Model Identification
ACF and PACF plots were used to identify candidate ARIMA models.

Model Selection
Several ARIMA models were tested using AIC and SSE metrics.

Best model selected:
ARIMA (2,0,2)

## Forecasting

The dataset was split into:

* 90% training data
* 10% testing data

The model was used for:

In-sample forecasting
Out-of-sample forecasting (14 days)

## Tools Used

R
quantmod
forecast
tseries
zoo
lubridate

## Skills Demonstrated

Time series analysis
Financial data modeling
ARIMA forecasting
Statistical testing
Financial analytics

## Author

Chitranjan Kumar
