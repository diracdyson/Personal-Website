---
title: Data Science Portfolio
---
# Projects:
# [Advanced clustering for Customer Segmentation](https://github.com/diracdyson/advancedCustomerSegmentationforclustering)
![](/umapg.png)
- Performed data exploration developing an intuition for the data with Box-Plots, bivariate scatter, correlation/ covariance heatmaps to detect large varaince and multicolienarity
- Applied advanced feature engineering techniques combining numerical features  and then applied PCA to reduce dimensionality even more; the n_components were found according to explained variance plot. Outliers which were 3 standard deviations outside of the mean were as well as missing values were removed since they were statistically insignificant only accounting for less than 1% of the sample
- Hyperparameter tuned industry favored cluster models for silhouette score by oveeriding GridSearchCV and created a function to do it fom scratch
- Found apporpirate cluster number by Kmeans SSE plot and found BIRCH to yield best customer segmentations
- Applied UMAP dimensionality reduction to view projected clusterings in 2-D place
# [Sales Time-Series Forecasting and Classifying a Clustering](https://github.com/diracdyson/Super-Store-EDA)
![](/box.png)
-  Found significant business discoveries during basic data exploration such as stores in Texas having negative profit in 2017 due to mainly selling large amounts of discounted binders at a loss
- Forecasted for monthly furniture sales under the SARIMAX Box-Jenkins methodology and also used Facebook's Prophet forecasting model
- Analyzed feature importance with MDI and permutation through classifying with RandomForest a K-Means clustering and found furniture as notably and unsurprisingly the most important feature
