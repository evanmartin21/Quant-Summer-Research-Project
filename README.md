# Quant Summer Research Project

A Python-based quantitative research project exploring market microstructure, derivatives pricing, numerical methods, and systematic trading.

The aim of this project is to develop practical quantitative research skills through empirical market analysis in the topics listed previously.

---

## Research Notebooks

1. Market Data Analysis
2. Time Series Analysis
3. Volatility Modelling (GARCH)
4. Black–Scholes Option Pricing
5. Binomial Tree Option Pricing
6. Greeks and Sensitivity Analysis
7. Monte Carlo Option Pricing
8. Market Microstructure Analysis
9. Order Book Dynamics
10. Final Research Report

---

## Completed Research

### Notebook 1 — Market Data Analysis

Topics covered:

- Download historical SPY data using Yahoo Finance
- Calculate daily and logarithmic returns
- Analyse return distributions
- Calculated annualised return and volatility
- Produced visualisations of price, returns and volatility
- Summarised statistical findings
- Investigate skewness and kurtosis
- Visualise financial time series

Key findings:

- Returns are negatively skewed
- Returns exhibit excess kurtosis
- Volatility clustering is clearly observed

---

### Notebook 2 — Time Series Analysis

Topics covered:

- Stationarity testing using the Augmented Dickey-Fuller test
- Rolling mean and rolling variance
- Autocorrelation Function (ACF)
- Partial Autocorrelation Function (PACF)
- ARIMA(1,0,1) modelling
- Five-day return forecasting
- Model evaluation

Key findings:

- Daily log returns are stationary
- Very little serial dependence exists
- ARIMA captures limited short-term linear structure
- Forecasts rapidly converge to the historical mean
- Financial returns exhibit changing volatility, motivating more advanced models such as GARCH

---

### Notebook 3 — Volatility Modelling (GARCH)

Topics covered:

- Review volatility clustering in financial returns
- Introduction to ARCH and GARCH models
- GARCH(1,1) model estimation
- Interpretation of ARCH and GARCH parameters
- Estimation of conditional volatility
- Comparison of estimated volatility with realised absolute returns
- Five-day volatility forecasting
- Model evaluation

Key findings:

- Financial market volatility exhibits strong persistence
- Estimated volatility closely tracks periods of heightened market activity
- The GARCH model successfully captures volatility clustering
- Volatility forecasts revert gradually towards the long-run equilibrium
- GARCH models are more appropriate than ARIMA models for modelling market risk
  
---
 
## Planned Research

- Market Microstructure
- Order book analysis
- Black–Scholes Option Pricing
- Binomial Tree Pricing
- Greeks Calculation
- Monte Carlo Simulation
- Volatility Surface Analysis
- Systematic Trading Strategy Backtesting

---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- pandas
- Matplotlib
- yFinance
- Statsmodels
- Arch
- Git & GitHub
- SciPy
- Scikit-Learn

---

## Author

Evan Martin
University of York