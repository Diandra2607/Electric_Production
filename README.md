# Background
This project deals with prediction of consumption of electricity in the coming future. Election Production forecast for 2019-2024 period using ARIMA will use Election Production 1985-2018 period. This case study focuses on the Willis Tower Watsons stock price prediction for 2019-2024.

# Time Series Plot
The first thing to do is create a time series plot. Before that, import the data. After import the data, create the time series plot. Based on the time series plot, the electricity production data has a seasonal pattern.

# Stationarity
The first step in forecasting with ARIMA is checking the variance and mean stationary. If the data is not variance and mean stationary, then the data must be transformed and differenced. The data's variance stationary is checked with the Box-Cox test while the data's mean stationary is checked with the ADF test. Based on the Box-Cox test, the Box-Cox value is around 1, which means the data is variance stationary. After that, test the mean stationary with ADF test. Based on the p-value in the ADF test, the data is mean stationary.

# Create ARIMA Model
After checking the variance and mean stationary, the next step is to create an ARIMA model. The first step is to determine the ARIMA order with ACF and PACF plot. Based on the ACF and PACF plot, the ARIMA order is ARIMA (12,0,1). After that, create an ARIMA (12,0,1) model.

# Forecast
After create an ARIMA (12,0,1) model, forecast the data for February 2018-January 2025 period.
