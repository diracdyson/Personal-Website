---
title: Data Science Portfolio
---
# [Advanced Clustering for Customer Segmentation](https://github.com/diracdyson/advancedCustomerSegmentationforclustering)
![](/umapg.png)
- Performed data exploration developing an intuition for the data with Box-Plots, bivariate scatter, correlation/ covariance heatmaps to detect large variance and multicolinearity
- Applied advanced feature engineering techniques by strategically combining numerical features of similar data collection and then applied PCA to reduce dimensionality even more
- Hyperparameter tuned sklearn cluster models for silhouette score and found apporpirate cluster number by Kmeans SSE plot and found a hyperparameter tuned BIRCH to yield best customer segmentations

# [Production level Customer Churn Classification](https://github.com/diracdyson/churn)
![](/churngroc.png)
- Feature engineered Kaggle data through a pipeline in Pandas and Scikit-learn removing irrelevant features, applied hot autoencoding to categorical features, standardized scaling to numerical features, over-sampling to rebalance target feature and principal component analysis
- Compared a plethora of production level models, but ultimately obtained a XGBoost and a customized Deep Neural Net model through hyperparameter grid search and shuffled K-fold cross validation both with 93 percent test accuracy on ROC curve


# [Store Sales Time-Series Forecasting and Classifying a Clustering](https://github.com/diracdyson/Super-Store-EDA)
![](/box.png)
-  Found significant business discoveries during basic data exploration such as stores in Texas having negative profit in 2017 due to mainly selling large amounts of discounted binders at a loss
- Forecasted for monthly furniture sales under the SARIMAX Box-Jenkins methodology and also used Facebook's Prophet forecasting model
- Analyzed feature importance with MDI and permutation through classifying with RandomForest a K-Means clustering and found furniture as notably and unsurprisingly the most important feature


# [House Price Forecasting and Feature Engineering Big Data](https://github.com/diracdyson/Housing-Price-Feature-Engineering-Forecasting)
![](/mdi.png)
- Utilized Pandas and Scikit-learn to perform feature engineering on a housing dataset with 83 features manipulating missing values, outliers, numerical and categorical features
- Forecasted for house price and selected features through exploiting LASSO Regression and analyzed feature importance with the aid of permutation and mean decrease in impurity by Random Forest Regressor via Scikit-learn
