# Housing-Dataset
Preprocessing and analysis of Boston Housing Dataset
The task is to see how well we can predict house price in the Boston Housing Dataset.  The dataset consists of 1460 records and 81 columns or variables.  After cleaning and preprocessing the data, two regression models will be used; Linear Regression and Random Forest Regressor.  The challenge with this dataset is the high dimensionality, i.e., 81 variables to work with.  The 81 variables are made up of continuous and categorical types.  Columns with high missing values are removed.  Then records with missing values are removed.  The explanatory variables are then chosen based on my own judgement.  The dependent variable is price.  The independent continuous variables are scaled using standardscaler.  Then the categorical variables are encoded using onehotencoder.  

# Linear Regression

