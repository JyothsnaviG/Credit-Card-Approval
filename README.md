# Credit-Card-Approval

The project aims to predict how likely a credit card request will get approved based on age, gender, credit score, income, debt, etc.

Exploratory Data Analysis - to understand the relationship among the features.

Build a machine learning model to predict if an applicantion can be approved or rejected . The imbalance data is a big problem in this task.

## Libraries Used
Pandas

Numpy

Matplotlib

Seaborn

sklearn

## Model Building
Built a dataframe with relevant columns.

Transformed the categorical variables into dummy variables. Then the data was split into train and test set.

Dealing with imbalanced data by oversampling with SMOTE.

## Models
Logistic Regression

Random Forest Classifier

Decision Tree Classifier

XGB Classifier

SVM Classifier

KNN Classification 

MLP Classifier

## Conclusion
We found out that XGBoost model is performing best with 89.82 % which is significantly high for predicting how likely a credit card application request will get approved.
