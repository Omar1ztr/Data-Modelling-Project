# Data-Modelling-Project
Time series forecasting of monthly grocery sales using Holt–Winters, Exponential Smoothing, and WMA.

# Grocery Sales Forecasting Using Time Series Models

## Project Overview
This project focuses on forecasting monthly grocery sales to support data-driven inventory, staffing, and purchasing decisions in a retail environment.

Using historical sales data and multiple related tables, the analysis identifies seasonality and trend patterns and evaluates which forecasting methods provide the most reliable predictions.

## Problem Statement
Grocery retailers face demand variability driven by seasonality, promotions, and product differences. Inaccurate forecasts lead to overstock, waste, stockouts, and poor labor planning.

The goal of this project is to forecast monthly sales for the top 5 revenue-generating products and identify the most accurate forecasting technique.

## Data & Preparation
- Integrated multiple tables:
  - Sales
  - Products
  - Employees
  - Cities
  - Countries
- Merged datasets using ProductID, CityID, and CountryID
- Identified the top 5 products by total revenue
- Extracted monthly revenue time series for each product

## Forecasting Methods
Three forecasting techniques were applied and compared:
- Weighted Moving Average (WMA)
- Exponential Smoothing
- Holt–Winters (Winters Method)

## Model Evaluation
Models were evaluated using:
- Mean Absolute Deviation (MAD)
- Mean Squared Error (MSE)
- Mean Absolute Percentage Error (MAPE)
- Forecast Bias

## Key Findings
- All top products exhibited strong seasonal patterns
- Holt–Winters consistently produced the lowest forecast error
- MAPE values were significantly lower than WMA and Exponential Smoothing
- Simple averaging methods underperformed for seasonal data

## Business Impact
Accurate forecasting enables:
- Improved inventory planning ahead of peak demand
- Reduced overstock and waste
- Better staffing and warehouse capacity decisions
- More reliable purchasing schedules

## Tools Used
- Excel (PivotTables, forecasting models)
- Power BI (dashboarding and visualization)
- Time Series Forecasting Techniques

## Author
Omar Ibraheem  
Data Analytics | Forecasting | Business Intelligence
