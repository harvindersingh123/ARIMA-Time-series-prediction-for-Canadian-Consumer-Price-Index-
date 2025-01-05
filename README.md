# ARIMA-Time-series-prediction-for-Canadian-Consumer-Price-Index-
# Canadian Consumer Price Index (CPI) Prediction Using ARIMA

## Overview
This project focuses on predicting the Canadian Consumer Price Index (CPI) using the ARIMA (AutoRegressive Integrated Moving Average) method. CPI is a key economic indicator that measures changes in the price level of a basket of consumer goods and services. By leveraging ARIMA, we aim to forecast future CPI trends and provide insights into inflation dynamics in Canada.

---

## Objectives
1. Analyze historical CPI data to understand trends and patterns.
2. Apply the ARIMA model to predict future CPI values.
3. Validate the model's performance using statistical metrics and visualizations.

---

## Data
The historical CPI data was sourced from official Canadian economic datasets, such as Statistics Canada. It includes monthly CPI values for a specified time range.

---

## Methodology
1. **Data Preparation**:
   - Import and clean the historical CPI dataset.
   - Check for missing or inconsistent values and handle them appropriately.

2. **Stationarity Check**:
   - Perform tests like the Augmented Dickey-Fuller (ADF) test to check for stationarity.
   - Apply differencing if necessary to make the time series stationary.

3. **Model Selection**:
   - Use Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots to determine the ARIMA parameters (**p**, **d**, **q**).
   - Fit the ARIMA model to the dataset.

4. **Forecasting**:
   - Predict future CPI values using the fitted ARIMA model.
   - Visualize predictions alongside historical data.

5. **Model Evaluation**:
   - Evaluate the model's performance using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
   - Compare predictions with actual values to assess accuracy.

---

## Tools and Libraries
- **Python**
- **Pandas** and **NumPy** for data manipulation
- **Matplotlib** and **Seaborn** for visualization
- **Statsmodels** for ARIMA modeling
