# Time-Series-Analysis
Mini projects in TSA

Two mini projects covering aspects of data analysis/time series analysis:

1) The first is `NASA_Sunspots.ipynb` that studies publicly available data on solar activity collected by NASA that plays around with a dataset that exhibits seasonality. We discuss some basic techniques used to reduce noice (resampling, rolling statistics) and make the time series stationary (differencing). We finally split the data into solar cycles and compare the behaviour over successive cycles.

2) The second is `CO2_Level_Forecast_SARIMA` that fits a seasonal ARIMA(p,d,q)(P,D,Q)s model to data on CO<sub>2</sub> levels collected at an observatory at Mauna Loa, Hawaii, between March 1998 and December 2001. We disscuss model selection from a grid-search of the parameters (p,d,q,P,D,Q) via the Akaike information criterion (AIC) and discuss goodness of fit by studying the residuals of the model. Finally, we use the selected model for forecasting CO<sub>2</sub> levels, including confidence intervals, and compare to the actual observed values.
