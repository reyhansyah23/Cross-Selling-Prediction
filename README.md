# Machine_Learning_Project

This project is a machine learning project of a prediction of cross selling dataset. The objective of the model is to predict whether health insurance policyholders are interested in vehicle insurance in the same company using the XGBoost model.

There are several technique that I used before modelling, such as:
- Processing categorical data by labelling the data on the features with numbers
- Processing numerical data using standard scaler method
- Oversampling data for imbalanced data using SMOTE algorithm
- Hyperparameter tuning using GridSearchCV to find an optimal parameters to be used in the XGBoost model

For modelling, I did a accuracy comparison between XGBoost with defaul parameter and parameter after doing the hyperparameter tuning (using the best parameter)
