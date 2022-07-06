# Forecasting taxi orders

#### Task: 
- To forecast the number of taxi orders for the next hour. It is necessary to build a model for such a prediction.

#### Description:
- A dataset with the number of taxi orders for six months (time series) was investigated. The data was resampled with an interval of 1 hour. 24 lagged features and a moving average calculated over the last 24 hours were added to the time series. Linear regression, random forest, gradient boosting (lightgbm and Catboost) models with hyperparameter fitting were trained on the training set. The best quality on the training data was shown by the LightGBM model with hyperparameters {'learning_rate': 0.1, 'max_depth': 4, 'n_estimators': 300} and RMSE=28.1. On test data, this model showed the value of the RMSE quality metrics equal to 41.2.

#### Status:
- Finished

#### Scope of Activities: 
- Retail / E-commerce, Taxi services, Advertisements, Internet shops, Business services [b2b], Startups, IT-company

#### Used Libraries:
- Pandas, sklearn, numpy, matplotlib, seaborn, LightGBM, CatBoost

#### Tags:
- data science, machine learning, ML, Python, Git, Pandas, Numpy, Matplotlib, seaborn, Sklearn, sci-py, Research, Algorithms, CatBoost, lgbm, light gbm, gradient boosting, nonlinear optimization, clustering, random forest, descision trees, regression