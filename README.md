# pm25-forecasting-johor


## Project Title
PM2.5 Forecasting in Johor Using Time Series Analysis

## Overview
Developed forecasting models for PM2.5 concentrations across eight air quality monitoring stations in Johor, Malaysia. The project compared seasonal and non-seasonal time series approaches to identify the most suitable forecasting model for each location and generate short-time air quality predictions.

## Business Problem
Poor air quality poses serious health risks and environmental challenges. Accurate PM2.5 forecasting can help policymakers and environmental agencies implement early warning systems and mitigation strategies.

## Dataset
### Source:
Department of Environment (DOE) Malaysia
### Coverage :
8 monitoring stations in Johor
### Period:
January 2021 - December 2021
### Frequency:
Daily PM2.5 concentrations

## Tools Used
- R
- RStudio
- forecast package
- tseries package
- Time Series Analysis
- ARIMA
- SARIMA

## Methodology 
1. Data preprocessing
2. Exploratory Data Analysis
3. Stationarity testing using ACF/PACF
4. ARIMA and SARIMA model development
5. Model selection using AIC
6. Residual diagnostics
7. Forecast accuracy evaluation
8. 14-day forecasting

## Key Results
- Forecasted PM2.5 concentrations for eight monitoring stations.
- Compared ARIMA and SARIMA forecasting performance.
- Evaluated models using RMSE, MAE and MAPE.
- Generated 14-day out-of-sample forecasts.
- Identified station-specific forecasting models.
