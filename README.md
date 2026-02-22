# Sales-Forecasting-Excel-ETS
Validated sales forecasting model in Excel (ETS vs MA), achieving 17.64% MAPE and 42% error reduction over baseline.

📊 Sales Forecasting using Excel (ETS vs Moving Average)
📌 Project Overview

This project demonstrates time-series sales forecasting using Microsoft Excel. The objective was to compare a baseline Moving Average model with an Exponential Smoothing (ETS) model using proper train-test validation.

🔍 Workflow

Data cleaning and monthly aggregation

Feature engineering (Lag, 3-Month Moving Average, Growth Rate)

Time-based Train/Test split

ETS forecasting using Excel's FORECAST.ETS()

Baseline comparison with Moving Average

Model evaluation using MAPE

Interactive Dashboard for visualization

📈 Model Performance
Model	MAPE
ETS	17.64%
MA_3	30.61%

ETS reduced forecasting error by approximately 42% compared to the baseline model.

🛠 Tools Used

Microsoft Excel

Time Series Analysis

Error Metrics (MAPE)

Dashboard Design

🎯 Key Insights

The ETS model captured seasonality and trend more effectively than a simple moving average, demonstrating the importance of model validation and baseline benchmarking.
