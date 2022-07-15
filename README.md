# Property-Price-Prediction-file
Objective: In this project we predict the price of property on the bases of square fit, longitude, latitude, resale, under-construction,BHK.

Language used: Python

ML library:1)Numpy   2)Pandas   3)Matplotlib  4)skit-learn  5)seaborn.

Ml model used: 1) Random forest regression

Description: (Step-by-step execution)-

Import all Necessary libraries.They are-Pandas , Numpy, Matplotlib, Seaborn.
Load Air Passenger Dataset which is a CSV file.
Describe() function is used to get details of dataset.
Do Data cleaning of loaded Dataset, we use following functions-
                a. Nunique(): This function is used to identify unique value in a dataset.
                b. Isnull(): This function is used to to identify null values if present in a dataset.
                
CorrMatrix() used to find  correlation between dependent variable and independent variables.
Removing Outliers using IQR and save pure data in variables.
import feature selection for selecting important features.
Split the data into train and test
Use Random Forest Regression to train the model
find the score to check the accuracy of the model
Import math
Check the performance of model we use MSE and RMSE.


                
                
                
