# Time Series Analysis of Amazon's Quarterly Revenues

This repository contains code for an in-depth time series analysis of Amazon's Quarterly Revenues from 2006 to 2020. The project explores various forecasting methods and validates their performance using statistical tests and metrics.

## Forecasting Methods Implemented

- **ARIMA (AutoRegressive Integrated Moving Average)**
- **MA (Moving Average)**
- **EWMA (Exponentially Weighted Moving Average)**
- **Holt's Linear Trend Model**
- **Holt-Winters Exponential Smoothing**
- **SARIMA (Seasonal ARIMA)**

## Key Steps in the Analysis

1. **Data Stationarity Confirmation:**
   - Applied ACF (AutoCorrelation Function) and PACF (Partial AutoCorrelation Function) plots.
   - Used Augmented Dickey-Fuller tests to ensure data stationarity.

2. **Residuals Validation:**
   - Analyzed residuals' normality through QQ plots and distribution analysis.
   - Ensured model assumptions for accurate forecasting.

3. **Performance Metrics:**
   - Achieved a minimum RMSE (Root Mean Squared Error) of $ 8.30 million with ARIMA.
   - Achieved an RMSE of $ 18.87 million with Holt-Winters, demonstrating robust predictive performance.
