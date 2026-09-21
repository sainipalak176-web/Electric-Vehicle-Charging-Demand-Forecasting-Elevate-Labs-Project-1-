# EV Charging Demand Forecasting
Author - Palak Saini 

## Project Overview

This project analyzes electric vehicle (EV) charging data to understand charging patterns and forecast future charging demand.

The project uses historical EV charging records to identify peak charging hours, weekday vs weekend usage, vehicle-type patterns, traffic and weather effects, and future charging demand.

## Objectives

- Analyze EV charging demand patterns
- Identify peak charging hours
- Compare weekday and weekend charging activity
- Analyze charging requests by vehicle type
- Study the relationship between charging demand and other factors
- Forecast future EV charging demand

## Dataset

The dataset contains EV charging station records including:

- Station ID
- Vehicle Type
- Arrival Time
- Charging Start and End Time
- Waiting Time
- Battery Capacity
- State of Charge
- Energy Consumed
- Charging Power
- Queue Length
- Station Load
- Electricity Price
- Traffic Density
- Weather Condition
- Charging Demand

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- VS Code

## Analysis Performed

1. Data loading and preprocessing
2. Date and time analysis
3. Hourly charging request analysis
4. Daily charging demand analysis
5. Weekday vs weekend analysis
6. Vehicle type analysis
7. Traffic density analysis
8. Weather condition analysis
9. Correlation analysis
10. EV charging demand forecasting

## Machine Learning

A Linear Regression model was used to forecast daily EV charging demand.

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

Model performance was evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

## Key Insights

The analysis helps identify:

- Peak charging periods
- Differences between weekday and weekend charging activity
- Charging patterns across vehicle types
- The relationship between charging demand and operational factors
- Expected future charging demand

## Project Structure

```text
EV_Charging_Demand_Forecasting/
│
├── ev_charging_dataset.csv
├── EV_Charging_Analysis.ipynb
└── README.md
