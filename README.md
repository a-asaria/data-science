# data-science
Repository for all my DS/ML experiments, with folders separating each project. For the moment I'm enjoying experimenting with different techniques I've learned over the years during my work, courses, and tutorials I've been doing - and seeing how they affect model performance

## Projects summary

### 2501-House Prices - Advanced Regression Techniques (Kaggle - Top 14% of submissions)
**Description:** Trying different techniques and regressor models to predict house prices

| Version  | Description | Test Score (RMSE of log(HousePrice)) |
| ------------- | ------------- | ------------- |
| [V4](https://github.com/a-asaria/data-science/blob/main/2501-House-Prices-Regression-Kaggle/250122-house-prices-4-stacked-model.ipynb)  | <ul><li>Combining multiple regressors into a VotingRegressor & StackingRegressor V1</li><li>To come back and explore this in more detail, due to slight decline in performance</li></ul> | <ul><li>0.12646 (+5.6%)</ul></li>  |
| [V3](https://github.com/a-asaria/data-science/blob/main/2501-House-Prices-Regression-Kaggle/250121-house-prices-3-with-gbregressor.ipynb)  | <ul><li>Do we get a better performance with a different (GradientBoostedRegressor with GridSearchCv) model?</li> | <ul><li>0.12576 (-13.2%)</ul></li>  |
| [V2](https://github.com/a-asaria/data-science/blob/main/2501-House-Prices-Regression-Kaggle/250121-house-prices-2-taking-log-of-feature.ipynb)  | <ul><li>Does converting the target variable to its log (to make it more normally distributed) help? (Yes)</li> | <ul><li>0.14498 (-1.0%)</ul></li>  |
| [V1](https://github.com/a-asaria/data-science/blob/main/2501-House-Prices-Regression-Kaggle/250120-house-prices-1.ipynb)  | <ul><li>Feature engineering and removing outliers</li><li>Random Forest Regressor with GridSearchCV to tune hyperparameters</ul></li> | <ul><li>0.1465</ul></li> |

### 2501-Playing with Tensorflow & MNIST dataset (Kaggle)
**Description:** Making some basic neural networks with Tensorflow to categorise handwritten digits from the MNIST dataset. I will return to this problem with more complex convolutional neural networks once I have picked up PyTorch, given the current trend towards that library

| Version  | Description | Test Accuracy |
| ------------- | ------------- | ------------- |
| [V2](https://github.com/a-asaria/data-science/blob/main/2501-Titanic/250113-titanic-random-forest-h-parameter-tuning.ipynb)  | <ul><li>Data augmentaion to increase size of training dataset & reduce overfitting </li><li>Adding single convolutional layer</li>  | <ul><li>98.5% (+5.4%)</ul></li>  |
| [V1](https://github.com/a-asaria/data-science/blob/main/2501-MNIST-Tensorflow/250114-minst-initial-play-around-score-0-931.ipynb)  | <ul><li>Basic neural network with dense layers</li><li>Reducing overfitting with L2 kernel regularizer</ul></li> | <ul><li>93.1% </ul></li> |

### 2501-Titanic (Kaggle - Top 19% of submissions)
**Description:** The classic Kaggle supervised  problem of predicting whether a set of passengers on the Titanic will survive

| Version  | Description | Test Accuracy |
| ------------- | ------------- | ------------- |
| [V3](https://github.com/a-asaria/data-science/blob/main/2501-Titanic/250117-w-feature-eng-selection.ipynb)  | <ul><li>More sophisticated feature engineering</li><li>Using XGBoost model, `early_stopping_rounds` to prevent overfitting  | <ul><li>78.2% (+0.7%)</li></ul>   |
| [V2](https://github.com/a-asaria/data-science/blob/main/2501-Titanic/250113-titanic-random-forest-h-parameter-tuning.ipynb)  | <ul><li>Including additional features </li><<li> Using GridSearchCV to tune hyperparameters  | <ul><li>77.5% (+0.2%)</li></ul>   |
| [V1](https://github.com/a-asaria/data-science/blob/main/2501-Titanic/250110-titanic-tutorial.ipynb)  | <ul><li>Familiarise myself with platform, using the Kaggle tutorial RF model with simple set of features </li></ul> | <ul><li>77.5%</ul></li>   |



