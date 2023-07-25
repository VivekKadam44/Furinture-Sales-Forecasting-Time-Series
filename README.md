# Furinture-Sales-Forecasting-Time-Series

## Overview

The goal of this project is to apply time series forecasting techniques to predict furniture sales for the next year using historical sales data. The project includes data preprocessing, time series analysis, and evaluation of different forecasting models.

## Dataset

The dataset used in this project is taken from Kaggle and contains historical sales data for various products, including furniture. The dataset can be found here: [Kaggle Dataset Link](https://www.kaggle.com/code/imkushwaha/project-forecasting-the-furniture-sales/input)

## Requirements

- Python 3.7 or higher
- pandas
- numpy
- matplotlib
- statsmodels
- pmdarima

## Project Stucture

The project is structured as follows:
├── data/
│   └── Sample - Superstore.xls (Sales data in Excel format)
├── notebooks/
│   ├── Time_Series_Forecast_Furniture_Sales.ipynb (Jupyter Notebook with code and explanations)
├── TimeSeriesOutput.xlsx (Forecasted sales data for the next 12 months)
├── README.md (This file)

## Time Series Analysis Techniques

The following time series analysis techniques are used in this project:
-Seasonal Decomposition: To identify the underlying components of the time series (trend, seasonality, and residual).
-Exponential Smoothing: For generating short-term forecasts based on trend and seasonality.
-Holt's Linear Exponential Smoothing: For handling trend and seasonality in a linear manner.
-SARIMA (Seasonal Autoregressive Integrated Moving Average): For capturing the seasonality and trend in a time series.

## Results
The forecasted sales data for the next 12 months provides valuable insights into the expected performance of furniture sales. The accuracy of the forecasts is evaluated using metrics such as Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).

## Note
Had issues with while importing pmdarima library because of internal clashing of libraries. In few days will upload the update code file. The code written will work properly if the library mentioned is installed already.
