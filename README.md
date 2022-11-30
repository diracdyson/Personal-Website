[![Repo](https://badgen.net/badge/icon/GitHub?icon=github&label)](https://github.com/diracdyson)
[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/brandonlee-santos/)


Welcome! This is my Data Science/ Financial Engineering portfolio. My GitHub contains a lot of other stuff.


About me:
- Recent graduate from Stony Brook University with a double major in Applied Mathematics and Statistics and Physics(May 2021)
- Seeking employment as a Quantitative Researcher/ Risk Analyst or Data Scientist/ Analyst
- I have completed various projects in Quantum Computing, Machine Learning and Quantitative Finance either through university, the Institute of Advanced Computational Science at Stony Brook University or independently. My strong suit lies in pure data science, which is more or less data analysis and statistical model development(classical stats, advanced ML, time-series) to solve financial business problems, although you can see I am a researcher at heart.
- Besides my more practical mainstream 'industrial' projects I still work on more theoretical statistics/ ML research topics, but more recently I have been trying to apply these more theoretical research ideas in practice effectively, which is rare but not unheard of and more often embraced in financial engineering and typically frowned upon in data science to use models from 'cutting edge' research papers. Anyhow, I am currently working on a research paper on anomaly detection on comparing classical stats(Tukey's fences) and modern day ML methods( VAE's, AE's, density methods, non-parametric methods) and providing a dynamic sophisticated methodolgical framework for anomaly detection in univariate time-series( potentially generalizes to n-dimensional time-series)


My current 'tech stack' in Python is the following:


- Data Analysis/Manipulation: Pandas, Seaborn, Matplotlib


- Model Development: NumPy, SciPy, Scikit-learn, Statsmodels, Keras, TensorFlow, PyTorch, ARCH, pdarima


[Current topics of interest](/skrt.md)



# [Financial Returns Analysis and Sharpe Ratio from Weighted Least Squares](https://github.com/diracdyson/Antarctica-Managment-Returns)
![](/heatant.png)
- This was real life returns data of a Hedge Fund and its strategies provided by Antarctica Asset Management
- Dealt with outliters by Z-score method and applied the generalized least sqaures method for heterosckedastic time-series data and deduced a better portfolio than the Hedge Fund from a CAPM multilinear regression model
- Dispersion analysis is used to decipher riskyness of portfolio


# [Exploratory Data Anaysis + Sales Time-Series Forecasting and Classifying a Clustering](https://github.com/diracdyson/Super-Store-EDA)
![](/box.png)
-  Found significant business discoveries during basic data exploration such as stores in Texas having negative profit in 2017 due to mainly selling large amounts of discounted binders at a loss
- Forecasted for monthly furniture sales under the SARIMAX Box-Jenkins methodology and also used Facebook's Prophet forecasting model
- Analyzed feature importance with MDI and permutation through classifying with RandomForest a K-Means clustering and found furniture as notably and unsurprisingly the most important feature


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
