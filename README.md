# fish-kill-predictive-system
A Microsoft Excel-based predictive system for fish kill occurrence using water quality variables.

# Fish Kill Predictive Warning System (Excel-Based)

This repository contains a Microsoft Excel-based predictive warning system developed using a logistic regression model to estimate the probability of fish kill occurrence.

# Input Variables
Users can input the following water quality variables:
- pH
- Dissolved Oxygen (DO)
- Nitrate
- Temperature
- Total Dissolved Solids (TDS)
- Conductivity
- Salinity
- Turbidity

# How It Works
The model computes the probability of fish kill occurrence based on user inputs and classifies the result using an optimized Youden Index threshold.

# File Included
- `Fish Kill Predictive Warning System.xlsx` – Main predictive tool

# Instructions
1. Open the Excel file
2. Enter values for the predictor variables
3. Click the “Enter” button to generate prediction
4. View classification result

# Notes
- Reduced models with fewer predictors are available in separate sheets
- Developed as part of a research study on fish kill prediction
