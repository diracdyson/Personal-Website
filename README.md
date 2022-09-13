Welcome!( Sorry currently under heavy construction)
# Current Areas of interest
- Semi/Unsupervised learning K-Means, LOF, DBSCAN, GMM, Transformers, AutoEncoders
- Supervised learning for forecasting and classification ANN, CNN, LSTM, Naive Bayes
- Ensemble methods Random Forest
- Dimension reduction methods PCA, and LDA
- Time-Series forecasting(Box Jenkins SARIMAX methodology, AR-GARCH vol forecasting)
- Stochastic Calculus( Stochastic vol models pricing for options, local vol)
- Numerical methods for simulating PDE's (finite diff. method)
- Feature engineering and Data Analysis with SQL, Pandas and Google Data Studio

# [Modern Portfolio Theory](https://github.com/diracdyson/VaRGARCH)
![](/Unknown-2.png)
- There are many ways to calulcate VaR such as historical bootstrapping, the classical Marokwitz way and advanced statistical methods
- In this project Classical Markowtiz theory is compared with time-series parametric methods GARCH developed from scratch and GARCH from the ARCH package with student - t dist.
- Value at Risk is computed three different ways using bootstrapping, Markowitz way and via GARCH


# [Heston Option Pricing](https://www.github.com/diracdyson/HESTON)
![](/Unknown-1-1.png)


![](/volsurf.png)

- The notrious Black Scholes models assummes Geometric Brownian Motion for the Stock Price, and  constructing a risk neutral portforlio then subbing in Ito's lemma allows one to derive a beta neutral pricing formula for a call or put
- This leads one to consider how to deal with the 'volatility smile' of the Black Scholes model
- In this project I conisder Geometric Brownian Motion for the volatility of the stock price, which in turns derives the Heston PDE
- I then fit the solution to the PDE to real world option data and extrapolate projections
- Theoretically this project was fascinating but as a practitioner it has major draw backs in that the market prices calibrated from Black Scholes are more accruate 
