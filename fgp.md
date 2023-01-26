---
Financial Engineering Portfolio
---
# Projects:
# [Financial Returns Analysis and Sharpe Ratio from Weighted Least Squares](https://github.com/diracdyson/Antarctica-Managment-Returns)
![](/heatant.png)
- This was real life returns data of a Hedge Fund and its strategies provided by Antarctica Asset Management
- Dealt with outliters by Z-score method and applied the generalized least sqaures method for heterosckedastic time-series data and deduced a better portfolio than the Hedge Fund from a CAPM multilinear regression model
- Dispersion analysis is used to decipher riskyness of portfolio

# [House Price Forecasting and Feature Engineering Big Data](https://github.com/diracdyson/Housing-Price-Feature-Engineering-Forecasting)
![](/mdi.png)
- Utilized Pandas and Scikit-learn to perform feature engineering on a housing dataset with 83 features manipulating missing values, outliers, numerical and categorical features
- Forecasted for house price and selected features through exploiting LASSO Regression and analyzed feature importance with the aid of permutation and mean decrease in impurity by Random Forest Regressor via Scikit-learn

# [Modern Portfolio Theory](https://github.com/diracdyson/VaRGARCH)
![](/Unknown-2.png)
- There are many ways to calulcate VaR such as historical bootstrapping, the classical Markowitz way and advanced statistical methods
- In this project Classical Markowtiz theory is compared with time-series parametric methods GARCH developed from scratch and GARCH from the ARCH package with student - t dist.
- Value at Risk is computed three different ways using bootstrapping, Markowitz way and via GARCH

# [Heston Option Pricing](https://www.github.com/diracdyson/HESTON)
![](/Unknown-1-1.png)
- The notrious Black Scholes models assumes Geometric Brownian Motion for the Stock Price; constructing a risk neutral portforlio then subbing in Ito's lemma allows one to derive a beta neutral pricing formula for a call or put
- This leads one to consider how to deal with the 'volatility smile' and time dynamic volatility that is not considered in the Black Scholes model
- In this project I conisder Geometric Brownian Motion for the volatility of the stock price, which in turns derives the Heston PDE, I then fit the solution to the PDE to real world option data and extrapolate projections
