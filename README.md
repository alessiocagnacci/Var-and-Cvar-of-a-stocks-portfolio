#VaR and CVaR of a Stock Portfolio
*Calculation of the Value at Risk and Conditional Value at Risk for a user-selected portfolio of stocks from Yahoo Finance*

I decided to use Python to compute these two risk measures in order to evaluate the maximum expected loss of a portfolio within a given confidence interval (VaR) and the average loss in the worst-case scenarios (CVaR).

For the latter, I used both Monte Carlo simulation and historical time series.

I used the package yfinance to export historical time series from Yahoo finance.

The stocks included in the portfolio and their weights can be modified by editing the first lines of the code; for the assets, the Yahoo Finance tickers must be used.
