# TMDB-Box-office-revenue

TMDB BOX OFFICE REVENUE prediction is challenging dataset because of the number of features and their importance. It takes lot of time to 
analyse the dataset and then to start to preprocess because of corelation between features. Due to this correlation, we can not even simply drop the features as they influce the accuracy of whole model.

This challenging dataset is taken from [kaggle](https://www.kaggle.com/c/tmdb-box-office-prediction). 

In the notebook, we first try to visualize all the features and their importance. Thne we do feature engineering by hot encoding few variables and also drop NaN and other noisy data. We then apply Machine learning models to predict and visualize the accuracy or fit of the model.

In this notebook, we use 2 machine learning models:
1. Simple Linear regression model
2. XGBoostRegressor model

We then predict the values and check the MAE, MSE and RMSE. We are able to conclude the results from both the models by looking at the error terms.

XGBoost uses 500 params but fits the dataset almost very well.
