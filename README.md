# FTSE 100 Extreme Risk Analysis using EVT and Macroeconomic Factors

## Overview
This project investigates extreme downside risk in the FTSE 100 index using Extreme Value Theory (EVT) and macroeconomic variables.

The study combines:
- Peaks Over Threshold (POT) for Extreme Value Analysis
- Generalized Pareto Distribution (GPD)
- Ordinary Least Squares regression (OLS)
- Logistic regression for extreme event prediction

## Objectives
- Model tail risk in FTSE 100 returns
- Estimate extreme losses using EVT
- Examine how macroeconomic factors influence extreme events

## Methodology

### 1. Data
- FTSE 100 daily returns from 2004 to 2024
- Macroeconomic variables:
  - Bank Rate
  - Yield Curve
  - Bond Yield
  - Inflation (CPI)
  - GDP
  - Unemployment
  - Exchange Rate

### 2. Extreme Value Theory (EVT)
- Loss is defined as negative returns
- Threshold selected using stability analysis (u ≈ 0.03)
- POT method applied
- GPD fitted to exceedances

### 3. Risk Measurement
- Return levels estimated for different return periods

### 4. Regression Analysis
- Binary variable for extreme events
- Logistic regression is used to model the probability of extreme losses
- Macroeconomic variables used as predictors

## Key Findings
- EVT provides a good fit for extreme losses
- Macroeconomic variables significantly affect the probability of extreme events
- Monetary conditions and inflation increase downside risk
- Economic growth reduces extreme risk

## Tools & Libraries
- Python (pandas, numpy)
- statsmodels
- pyextremes
- matplotlib


## Future Work
- Extend to use in investment portfolios
- Can use better frequency data
- Apply machine learning models to tail prediction

## Author
Linh Nguyen  
MSc Risk Analytics, QMUL
