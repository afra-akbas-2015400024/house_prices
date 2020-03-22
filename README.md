# Prediction of house prices - Kaggle

In this repository, I try to predict the price of houses. I used [Kaggle dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) for training and testing my project. With different regression techniques, we can estimate the price of a house and use it in several fields. I used [Decision Tree Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html), and [Gradient Boosting Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html?highlight=gradient#sklearn.ensemble.GradientBoostingRegressor) in my project so that we can see the performance of these two regressors.

I have also kernel of this project in Kaggle, you can find [here.](https://www.kaggle.com/afraakbas/kernel6f1a8ea054/notebook)

![kaggle-image](https://camo.githubusercontent.com/7340ec20877100293b63728c5b56fcf57db2d2b9/687474703a2f2f6d2e717069632e636e2f7073623f2f563130376b686c4d31624c594d6e2f51716b555135694950664e4567355666656d444b7673566d7a7333442a3858616448494a36344a33756d51212f622f64416742414141414141414126626f3d73774e6c4167414141414144422a55212672663d7669657765725f34)


The procedure I follow:
          
1. Visualization of data and correlation between features
2. Data cleaning
     1. Drop missing data
3. Feature engineering
     1. Drop outliers
     2. Decreasing skewness 
4. Modeling & Evaluation
5. Submission
