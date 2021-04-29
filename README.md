# [Predict_People_Salary Project OverView](https://github.com/FrankDTS/Predict_Perple_Salary/blob/main/Predict_Salary_Project.ipynb)
 * Built several Machine Learning models (Logistic Regression, RandomFordst, and XGboost) to predict whether a person makes over 50K a year
 * Several Feature Engineering methods to fill with columns that have NA values.

# Code and Resoused Used
  * Python 3.8
  * Packages: pandas, numpy, seaborn, matplotlib, sklearn, Xgboost
  * [Xgboost parameter] (https://xgboost.readthedocs.io/en/latest/parameter.html)
  * [Data] (https://archive.ics.uci.edu/ml/index.php)
  
# Data Preprocessing
  1. Normalize or use logistic to transform the numeric columns (age, fnlwgt, education_number, hours)
  2. Group approximate equal columns to groups to reduce the dimension (workclass, martial_status, native_country)
     1. workclass: replace 'Without pay' and 'Never-worked' classes to 'Non-pay' class
     2. martial_status: replace 'Divorced' and class to 'Seperated' class
     3. native_country: use continent to group each country.
     
  3. one-hot encoding for categorical parameters
  4. Built Xgboost model to predict workclass, occupation, and native_country's Null value


# Fit and Predict models
  1. Logistic model
  2. RandomForest model
  3. Xgboost model
