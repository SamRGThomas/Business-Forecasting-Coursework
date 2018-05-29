# Business-Forecasting-Coursework
Business forecasting coursework created as part of my "Business Statistics and Forecasting" module to forecast time-series from the M3 forecasting competition.

Uses toolbox of 10 forecasting methods. The code selects one of the Arima, Theta, Exponential smoothing or linear regression models in the toolbox to forecast each data set. The selection is based on properties of the data; e.g. autoregression, and in-sample accuracy (through cross-validation). A novel insight is that the cross-validation, being a rolling origin, is weighted in favour of models that well predict later origins in the timeseries - the MAPE of the final origin bears more weighting in the overall in-sample MAPE score than the first origin.
