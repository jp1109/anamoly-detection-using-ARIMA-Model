Anomaly Detection in Time Series using ARIMA

This project focuses on detecting anomalies in univariate time series data using the ARIMA (AutoRegressive Integrated Moving Average) model. We use a real-world temperature dataset to demonstrate how statistical forecasting can help identify unexpected deviations or "anomalies" in data trends.

The pipeline includes:
- Time series visualization and stationarity checks
- Differencing to make the series stationary
- ACF & PACF plots to choose ARIMA parameters (p,d,q)
- Forecasting with ARIMA and residual error analysis
- Anomaly detection based on residual thresholds (2σ rule)
- Evaluation using RMSE and MAE

This method is valuable in domains like finance, IoT, environmental monitoring, and web analytics — wherever unexpected behavior in temporal data needs to be flagged.
