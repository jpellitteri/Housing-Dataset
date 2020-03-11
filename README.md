# Housing-Dataset
Preprocessing and analysis of Boston Housing Dataset
The task is to see how well we can predict house price in the Boston Housing Dataset.  The dataset consists of 1460 records and 81 columns or variables.  After cleaning and preprocessing the data, two regression models will be used; Linear Regression and Random Forest Regressor.  The challenge with this dataset is the high dimensionality, i.e., 81 variables to work with.  The 81 variables are made up of continuous and categorical types.  Columns with high missing values are removed.  Then records with missing values are removed.  The explanatory variables are then chosen based on my own judgement.  The dependent variable is price.  The independent continuous variables are scaled using standardscaler.  Then the categorical variables are encoded using onehotencoder.  I created a split test set with 20% of the data assigned to the test data for cross-validation. 

# Linear Regression
I first used Linear Regression, a common supervised machine learning algorithm.  The results were 85% variance score, which means the change in variables I chose for X explain 85% of the change in the y variable, price.  

# Random Forest Regression
Random Forest Regression is an ensemble machine learning method that aggregates results of many decision trees to reduce over-fitting.  At first I used 500 decision trees in the algorithm.  I increased the decision trees to 1000 which only increased the accuracy to 85%, the same as the linear regression results.  

# Recommendation
For further analysis, I would experiment with using more of the variables in the dataset to predict house pricing.  Principal Component Analysis might be beneficial to scale down the features and get a more simplified model.  


