# In-app-prediction
Predict whether users will purchase in the next 7 days and 14 days using machine learning models 


## Data pre-processing
The goal of this project is to predict whether or not a user will make a purchase within the next 7 or 14 days. In order to accomplish this, our team used app data to perform EDA, constructed user specific features, generate labels for the users, and then build machine learning models to predict those labels.


## Modeling
The models were evaluated using AUC score, which is a metric that penalizes based on level of confidence for incorrect predictions. Our team’s best model used the Random Forest algorithm to achieve an AUC score of 0.9978. The most useful features used in training this model were time-specific features relating to a user’s purchases and activity on the site.

## Data source
The data comes from user logs of a mobile app. Data was provided on app users created between October 1st, 2018 and December 14th, 2018 in the form of four csv files, each containing different types of data on users and their activity on the app
