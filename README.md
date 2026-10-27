# Market Risk Measurement and Stress Testing

## Project Overview

This project analyses market risk using NIFTY 50, India VIX, and US VIX data. It examines historical returns, volatility patterns, downside risk, and the relationship between market volatility and NIFTY 50 returns.

## Objectives

- Analyse NIFTY 50 daily returns and market volatility.
- Calculate historical Value at Risk (VaR) and Expected Shortfall (ES).
- Evaluate VaR using out-of-sample backtesting.
- Compare returns across normal- and high-volatility regimes.
- Estimate regression-based stress scenarios using India VIX and US VIX.
- Evaluate regression performance on a chronological test dataset.

## Methodology

1. Data cleaning and date alignment.
2. Daily log-return and volatility-change calculations.
3. Descriptive statistics and visualisation.
4. Historical and parametric VaR and Expected Shortfall.
5. Rolling historical VaR backtesting.
6. Volatility-regime comparison and statistical tests.
7. Regression modelling and out-of-sample evaluation.
8. Scenario-based market stress testing.

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- SciPy

## Repository Structure

- `Untitled10.ipynb` — analysis notebook
- `figures/` — exported graphs
- `results/` — result tables and CSV files
- `data/` — cleaned data or data-source instructions

## Limitations

The regression and stress-testing results are exploratory and depend on the quality of the input data and model assumptions. Stress scenarios are hypothetical, not guaranteed forecasts. The relationship between volatility indices and NIFTY returns should not be interpreted as causal without further analysis.

## Reproducibility

Open the notebook in JupyterLab, ensure the required libraries and input datasets are available, and run the cells in order.

## Author

Valathappan G

*Academic project in market risk measurement and stress testing.*
