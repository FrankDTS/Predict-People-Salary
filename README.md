# Predict_Perple_Salary- Project OverView
  * Built several Machine Learning (Logistic Regression, RandomFordst, and XGboost) to predict whether a person makes over 50K a year
  * Several Feature Engineering methods to fill with columns which have NA values. 

# Code and Resoused Used
  * Python 3.8
  * Packages: pandas, numpy, seaborn, matplotlib, sklearn, Xgboost
  * [Xgboost parameter] (https://xgboost.readthedocs.io/en/latest/parameter.html)
  
# Data Preprocessing
  1. Normalize or use logistic to transform the numeric columns (age, fnlwgt, martial_status, hours)
  3. Group approximate equal columns to groups to reduce the dimension (workclass, education_number, captial)
  4. native_country is the most difficult transformation in categorical parameter, I use continent to group each country.
  5. one hot encoding for categorical paramete


# Fit and Predict models
  1. Logistic model
  2. RandomForest model
  3. Xgboost model
