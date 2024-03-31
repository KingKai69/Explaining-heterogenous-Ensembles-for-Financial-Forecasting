# Explaining Heterogenous Ensembles for Financial Forecasting

This repository contains source code and dataseta to reproduce the results of my Masterthesis.

Please find the champagne sales dataset here: https://www.kaggle.com/datasets/piyushagni5/monthly-sales-of-french-champagne

1. Use Simulation_blackbox_forecast.ipynb to create a simulated blackbox forecast
2. Use Surrogate_model_explainability.ipynb to create a surrogate model and related explanations

With the notebook Simulation_blackbox_forecast.ipynb a black box forecast is simulated by creation of a forecast by arima and prophet and averaging the predictions. Therefore 3 years of Champagne_Sales.csv are used as training data to predict the 5 following years. Those 60 datapoints serve as training data for the surrogate model. BlackBox_forecast_simulation.csv contains the time series with average predictions of arima and prophet.
