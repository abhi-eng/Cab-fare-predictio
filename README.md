# Cab-fare-prediction
Predicting the cab fare by using machine learning algorithms.
 GitHub folder contains: 
 1. R code of project in ‘.R format’: cab project using r.R
2. Python code of project in ‘.ipynb format’: cab project using
python.ipynb
3. Project report: cab project.pdf
4. Saved Model trained on entire training dataset from python:
cab_fare_xgboost_model.rar
5. Saved Model trained on entire training dataset from python:
final_Xgboost_model_using_R.rar
6.For R, Predictions on test dataset in csv format:predictions_xgboost
using R.csv
7.For python,Predictions on test dataset in csv format:predictions_xgboost
using python.csv

## Problem Statement 
 
The objective of this Project is to Predict Cab Fare amount based upon following data attributes in the dataset are as follows:

    pickup_datetime - timestamp value indicating when the cab ride started.
    pickup_longitude - float for longitude coordinate of where the cab ride started.
    pickup_latitude - float for latitude coordinate of where the cab ride started.
    dropoff_longitude - float for longitude coordinate of where the cab ride ended.
    dropoff_latitude - float for latitude coordinate of where the cab ride ended.
    passenger_count - an integer indicating the number of passengers in the cab ride.


### It is a regression Problem.
## All the steps implemented in this project
1. Data Pre-processing.
2. Data Visualization.
3. Outlier Analysis.
4. Missing value Analysis.
5. Feature Selection.
 -  Correlation analysis.
 -  Chi-Square test.
 -  Analysis of Variance(Anova) Test
 -  Multicollinearity Test.
6. Feature Scaling.
 -  Normalization.
7. Splitting into Train and Validation Dataset.
8. Hyperparameter Optimization.
9. Model Development
I. Linear Regression 
II. Ridge Regression 
III. Lasso Regression 
IV. Decision Tree 
V. Random Forest 
10. Improve Accuracy 
a) Algorithm Tuning
b) Ensembles------XGBOOST For Regression
Finalize Model 
a) Predictions on validation dataset 
b) Create standalone model on entire training dataset 
c) Save model for later use
11. Python Code
