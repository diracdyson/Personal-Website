[![Repo](https://badgen.net/badge/icon/GitHub?icon=github&label)](https://github.com/diracdyson)
[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/brandonlee-santos/)



Welcome! This is my Data Science/ Financial Engineering portfolio. Check out my GitHub.


# [Banking Churn Classification](https://github.com/diracdyson/churn)
![](/roccurve.png)
- Feature engineered dataset in Pandas and Scikit-learn removing irrelevant features, applying hot autoencoding to categorical features, standardized scaling to numerical features, over-sampling to rebalance target feature and principal component analysis 
- Compared a plethora of models, but ultimately obtained a XGBoost model through hyperparameter grid search and K-fold cross validation with above 90 percent test accuracy


# [Financial Returns Analysis and Sharpe Ratio from Weighted Least Squares](https://github.com/diracdyson/Antarctica-Managment-Returns)
![](/heatant.png)
- This was real life returns data of a Hedge Fund and its strategies provided by Antarctica Asset Management
- Dealt with outliters by Z-score method and applied the generalized least sqaures method for heterosckedastic time-series data and deduced a better portfolio than the Hedge Fund from a CAPM multilinear regression model
- Dispersion analysis is used to decipher riskyness of portfolio

# [House Price Forecasting and Feature Engineering Big Data](https://github.com/diracdyson/Housing-Price-Feature-Engineering-Forecasting)
![](/mdi.png)
- Utilized Pandas and Scikit-learn to perform feature engineering on a housing dataset with 83 features manipulating missing values, outliers, numerical and categorical features
- Forecasted for house price and selected features through exploiting LASSO Regression and analyzed feature importance with the aid of permutation and mean decrease in impurity by Random Forest Regressor via Scikit-learn

# [Exploratory Data Anaysis + Sales Time-Series Forecasting and Classifying a Clustering](https://github.com/diracdyson/Super-Store-EDA)
![](/box.png)
-  Found significant business discoveries during basic data exploration such as stores in Texas having negative profit in 2017 due to mainly selling large amounts of discounted binders at a loss
- Forecasted for monthly furniture sales under the SARIMAX Box-Jenkins methodology and also used Facebook's Prophet forecasting model
- Analyzed feature importance with MDI and permutation through classifying with RandomForest a K-Means clustering and found furniture as notably and unsurprisingly the most important feature

# [Modern Portfolio Theory](https://github.com/diracdyson/VaRGARCH)
![](/Unknown-2.png)
- There are many ways to calulcate VaR such as historical bootstrapping, the classical Markowitz way and advanced statistical methods
- In this project Classical Markowtiz theory is compared with time-series parametric methods GARCH developed from scratch and GARCH from the ARCH package with student - t dist.
- Value at Risk is computed three different ways using bootstrapping, Markowitz way and via GARCH

# [Heston Option Pricing](https://www.github.com/diracdyson/HESTON)
![](/Unknown-1-1.png)
- The notrious Black Scholes models assummes Geometric Brownian Motion for the Stock Price; constructing a risk neutral portforlio then subbing in Ito's lemma allows one to derive a beta neutral pricing formula for a call or put
- This leads one to consider how to deal with the 'volatility smile' and time dynamic volatility that is not considered in the Black Scholes model
- In this project I conisder Geometric Brownian Motion for the volatility of the stock price, which in turns derives the Heston PDE, I then fit the solution to the PDE to real world option data and extrapolate projections




Below are some of the topics I have covered relating to machine learning and financial engineering(Sorry currently under heavy construction)
# Statistical and Applied Machine Learning for Data Science
- Semi/Unsupervised learning K-Means, LOF, DBSCAN, GMM, Transformers, AutoEncoders, VAE's
- Supervised learning for forecasting and classification ANN, CNN, LSTM, GDA
- Ensemble methods CART, Random Forest, AdaBoost
- Dimension reduction methods PCA, and LDA
- Feature engineering and Data Analysis preprocessing with SQL, Pandas and Google Data Studio
- Matrix Profile
# Financial Engineering
- Time-Series forecasting Box Jenkins SARIMAX methodology, AR-GARCH vol forecasting with rolling window validation
- Stochastic Calculus volatility modeling
- Numerical methods for simulating PDE's finite diff. method
- Value At Risk, CVaR in classical finance/stats and copulas
- Machine learning copulas
- Kalman Filter
# More specific topics of interest
- Outlier detection in unsupervised learning( writing a paper on this)
- LM, Wald, LR hypothesis test methods( making your own Hypothesis test)
