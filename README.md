# Quant Summer Research Project

A Python-based quantitative research project exploring market microstructure, derivatives pricing, numerical methods, and systematic trading.

The aim of this project is to develop practical quantitative research skills through the implementation of financial models, empirical market analysis and statistical techniques commonly used in quantitative research and quantitative trading

The project combines mathematical derivations, statistical modelling and Python implementations, with each notebook documenting both the underlying theory and practical application.

---

## Research Notebooks

1. Market Data Analysis
2. Time Series Analysis
3. Volatility Modelling (GARCH)
4. Black–Scholes Option Pricing
5. Binomial Tree Option Pricing
6. Monte Carlo Option Pricing
7. Greeks and Sensitivity Analysis
8. Market Microstructure Analysis
9. Order Book Dynamics
10. Final Research Report

---

## Completed Research

### Notebook 1 — Market Data Analysis

Topics Covered:

- Download historical SPY data using Yahoo Finance
- Calculate daily and logarithmic returns
- Analyse return distributions
- Calculated annualised return and volatility
- Produced visualisations of price, returns and volatility
- Summarised statistical findings
- Investigate skewness and kurtosis
- Visualise financial time series

Key Findings:

- Returns are negatively skewed
- Returns exhibit excess kurtosis
- Volatility clustering is clearly observed

---

### Notebook 2 — Time Series Analysis

Topics Covered:

- Stationarity testing using the Augmented Dickey-Fuller test
- Rolling mean and rolling variance
- Autocorrelation Function (ACF)
- Partial Autocorrelation Function (PACF)
- ARIMA(1,0,1) modelling
- Five-day return forecasting
- Model evaluation

Key Findings:

- Daily log returns are stationary
- Very little serial dependence exists
- ARIMA captures limited short-term linear structure
- Forecasts rapidly converge to the historical mean
- Financial returns exhibit changing volatility, motivating more advanced models such as GARCH

---

### Notebook 3 — Volatility Modelling (GARCH)

Topics Covered:

- Review volatility clustering in financial returns
- Introduction to ARCH and GARCH models
- GARCH(1,1) model estimation
- Interpretation of ARCH and GARCH parameters
- Estimation of conditional volatility
- Comparison of estimated volatility with realised absolute returns
- Five-day volatility forecasting
- Model evaluation

Key Findings:

- Financial market volatility exhibits strong persistence
- Estimated volatility closely tracks periods of heightened market activity
- The GARCH model successfully captures volatility clustering
- Volatility forecasts revert gradually towards the long-run equilibrium
- GARCH models are more appropriate than ARIMA models for modelling market risk
  
---

### Notebook 4 — Black–Scholes Option Pricing

Topics Covered:

- European call and put option payoffs
- Black–Scholes pricing formulas
- Python implementation of the model
- Interpretation of $d_1$ and $d_2$
- Put–call parity validation
- Option payoff diagrams
- Application to a real Mini-SPX European option
- Comparison between the theoretical price and market midpoint
- Discussion of model assumptions and limitations

Key Findings:

- The Python implementation satisfies put–call parity
- Option value before expiration differs from payoff at maturity
- Black–Scholes provides a useful theoretical benchmark for European options
- The selected real-market option produced a theoretical price of 22.32 compared with a market midpoint of 20.44 and a percentage error of 9.25%

---

### Notebook 5 - Binomial Tree Option Pricing

Topics Covered:

- One-period binomial option pricing
- Risk-neutral valuation
- Cox–Ross–Rubinstein parameter derivation
- Multi-step recombining stock price trees
- Backward induction algorithm
- European call option pricing
- Comparison with the Black–Scholes analytical solution

Key Findings:

- Built a recombining binomial stock price tree in Python
- Implemented backward induction to value European options
- Validated the implementation against the Black–Scholes model within a 3.4% error

--- 

### Notebook 6 - Monte Carlo Option Pricing

Topics Covered:

- Geometric Brownian Motion
- Risk-neutral valuation
- Exact solution of GBM
- Monte Carlo simulation algorithm
- European call and put option pricing
- Comparison with the Black–Scholes model

Key Findings:

- Derived the risk-neutral Monte Carlo pricing framework from Geometric Brownian Motion.
- Implemented a Monte Carlo simulator for European call and put options in Python.
- Estimated option prices by averaging discounted simulated payoffs.
- Validated the implementation against the Black–Scholes analytical solution, obtaining a relative difference of approximately 0.42%.

## Technologies Used

Development Environment:

- Python
- Jupyter Notebook

Data Analysis: 

- NumPy
- pandas
- SciPy

Financial Data:

- yfinance

Statistical Modelling:

- statsmodels
- arch
- scikit-learn

Visualisation:

- Matplotlib

Version Control:

- Git
- GitHub


---

## Author

Evan Martin
University of York