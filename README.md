# Predicting House Sales Prices Using Advanced Regression Techniques

I used feature engineering and advanced regression techniques to build machine learning models to predict final home sales prices. The dataset I used consisted of 79 variables describing features of homes in Ames, Iowa.

This project and its dataset was based on a Kaggle competition: https://www.kaggle.com/c/house-prices-advanced-regression-techniques

I did two versions of the project: an original and a more recently revised version.

Version 1: 

I accessed the dataset using PostgreSQL and used Pandas for exploratory data analysis and data cleaning. 

From the scikit-learn library, I used PCA to explain the variance of the data and do dimensionality reduction. I used KMeans to cluster the data and KNeighborsClassifier to build a predictive model. I then built a series of grid-searched tree-based models. My benchmark test accuracy score, using an untuned Decistion Tree Regressor model, was 68%. I was able to improve the accuracy of this model by using GridSearchCV to tune the hyperparameters, resulting in a (test) score of 72%.

Note: this was the second project I did for the Data Science Immersive prorgram at General Assembly.

Version 2:

I focused on doing better pre-processing and feature selection. I used Lasso and GradientBoostingRegressor and obtained the most important features in predicting sale price. My best accuracy score (R^2) was 91% with a RMSE of around $20,000 average difference between the predicted and actual sale prices.
