# TimeSeriesAnalysis-dailytemp
# Project Description

This project is an experimental Data Science side project using Python to conduct Time Series Analysis and Weather Forecasts.
# Data Source

The data have been downloaded from the website https://www.kaggle.com/datasets/paulbrabban/daily-minimum-temperatures-in-melbourne.To predict the daily temperature in Melbourne using 10 years data.
# Approach
checked for Auto/serial correlation by Acf and lag
plots, stationarity by Adfuller, seasonality or any trend by seasonal decompose visualization.
1-step prediction model has taken as baseline model, Used RMSE as performance measure.
Applied the SARIMA and AR model. Used Grid search and lag vs error plots for optimum lag value.
Finally,SARIMA is decided by visualizing the prediction results from all three models.
