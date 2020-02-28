# Prediction of house prices - Kaggle

In this repository, I try to predict the price of houses. I used [Kaggle dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) for training and testing my project. With different regression techniques, we can estimate the price of a house and use it in several fields.
I used [Decision Tree Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html), and [Gradient Boosting Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html?highlight=gradient#sklearn.ensemble.GradientBoostingRegressor) in my project so that we can see the performance of these two regressors.

The procedure I follow:
          
1. Visualization of data and correlation between features
2. Data cleaning
     1. Drop missing data
3. Feature engineering
     1. Drop outliers
     2. Decreasing skewness 
4. Modeling & Evaluation
5. Submission
