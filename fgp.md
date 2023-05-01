---
title: Financial Engineering Portfolio
---

# [ NumerAI Hedge Fund](https://numer.ai/brsantos1)
![](/numeraires.png)
- Achieved 97th percentile amongst professional quantitative researchers and data scientists in a daily forecasting tournament in which the Hedge Fund NumerAI relies upon for their own Portfolio adjustments
- Developed an object-oriented data and model pipeline which performs preprocessing, model based feature engineering/selection, hyperparameter tuning through cross-validation with Time-Series techniques and lastly submits the predicted forecast reliant upon state-of-the-art research techniques 
- I am an active participant due to the competitive nature and economic incentives I do not share the current code I show only an old Toy Model; some people do this as a part time job


# [Factor Portfolio Weighted Least Squares and Advanced Forecasting](https://github.com/diracdyson/Antarctica-Managment-Returns)
![](/heatant.png)
- This was real life returns data of a Hedge Fund and its strategies provided by Antarctica Asset Management
- Dealt with outliters by Z-score method and applied the generalized least sqaures method for heterosckedastic time-series data and deduced a better portfolio than the Hedge Fund from a CAPM multilinear regression model
- Forecasted for Hedge Fund returns using econometric models built from scratch in NumPy such as Random Forest Regressor, XGBoost, SARIMAX-GARCH and using TensorFlow a transformer

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
