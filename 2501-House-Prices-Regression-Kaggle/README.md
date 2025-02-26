### 2501-House Prices - Advanced Regression Techniques (Kaggle - Top 12% of submissions)
**Description:** Trying different techniques and regressor models to predict house prices

| Version  | Description | Test Score (RMSE of log(HousePrice)) |
| ------------- | ------------- | ------------- |
| [V6](https://github.com/a-asaria/data-science/blob/main/2501-House-Prices-Regression-Kaggle/250121-house-prices-5-2-select-x.ipynb)  | <ul><li>Can I improve the original GradientBoostingRegressor performance, by using SelectFromModel to select fewer features and trying to reduce overfitting?</li><li>Not so far</li></ul> | <ul><li>0.134</ul></li>  |
| [V5](https://github.com/a-asaria/data-science/blob/main/2501-House-Prices-Regression-Kaggle/250122-house-prices-4-stacked-model.ipynb)  | <ul><li>Can I improve performance by combining additional regressors with the voting regressor as a stacking regressor?</li><li>Not so far</li></ul> | <ul><li>0.12646</ul></li>  |
| [V4](https://github.com/a-asaria/data-science/blob/main/2501-House-Prices-Regression-Kaggle/250121-house-prices-4-1-voting-model.ipynb)  | <ul><li>Combining multiple regressors into a VotingRegressor</li></ul> | <ul><li>**0.12448 (-1.0%)**</ul></li>  |
| [V3](https://github.com/a-asaria/data-science/blob/main/2501-House-Prices-Regression-Kaggle/250121-house-prices-3-with-gbregressor.ipynb)  | <ul><li>Do we get a better performance with a different (GradientBoostedRegressor with GridSearchCv) model?</li> | <ul><li>0.12576 (-13.2%)</ul></li>  |
| [V2](https://github.com/a-asaria/data-science/blob/main/2501-House-Prices-Regression-Kaggle/250121-house-prices-2-taking-log-of-feature.ipynb)  | <ul><li>Does converting the target variable to its log (to make it more normally distributed) help? (Yes)</li> | <ul><li>0.14498 (-1.0%)</ul></li>  |
| [V1](https://github.com/a-asaria/data-science/blob/main/2501-House-Prices-Regression-Kaggle/250120-house-prices-1.ipynb)  | <ul><li>Feature engineering and removing outliers</li><li>Random Forest Regressor with GridSearchCV to tune hyperparameters</ul></li> | <ul><li>0.1465</ul></li> |
