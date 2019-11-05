# This is a project that has been done on Investigation of Airbnb activity in Berlin

## Steps involved:
   
##  Data Sets:
  Two datasets in the form of csv files have been used in this work
  1) listings_summary.csv This contains all the list of various appartments and as many as 96 different attributes 

  2) reviews_summary.csv This dataset contains data for the various customer reviews based on their experince of stay 

## Data Cleaning
   1)  The given datasets were cleaned as there were many missing values by filling with 0 or mean values as and were applicable
   2)  The dataset of customer review was cleaned as the reviews has various special symbols,stop words ,puntuations and steming was done to get the stem words

##  Feature Engineering
   1)This was a very essential step as listings_summary.csv had initially 96 columns from which after performing Exploratory Data Analysis it was concluded that only 20 columns are relevant to work with
   2)Feature extraction from the existing features was also performed

##   Applying the machine learning models
    1)The data set is split into train and test set  and various algorithms are used
    
    2) The algorithms are:
       1.	Linear Regression
       2.	Random Forest
       3.	Gradient Boosting
              a.	XGBoost
              b.	LGBM

    2) RMSE and R2 scores are computed

###   Applying Hyperparameter-tuning and Cross validation on models

###   Getting the final test rmse mean and standard deviation

###    For review classification logistic regression is used

