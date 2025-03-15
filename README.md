# Home-Price-Prediction
Project Summary :- 

This project focuses on predicting property prices using Linear Regression. The dataset includes various property-related features such as number of bedrooms, bathrooms, land size, and building area. The goal is to train a model that can accurately estimate housing prices based on these attributes.
 
Project Details:

1. Data Processing:-
The dataset is loaded using Pandas.
Unnecessary columns such as Address, Date, Postcode, YearBuilt, Latitude, and Longitude are dropped.
Missing values in numerical columns like Landsize and BuildingArea are filled with their respective mean.
Other missing values in categorical/numeric columns are filled with 0.
The dataset is converted into a machine-learning-friendly format using one-hot encoding.

2. Model Training:-
The target variable (Price) is separated from the features.
The dataset is split into training and testing sets using train_test_split().
A Linear Regression model is trained to predict housing prices.
Model evaluation is likely performed using metrics like R² score and Mean Absolute Error (MAE).

3. Features Used:-
The following features contribute to the prediction:

Propertycount
Distance
Bedroom2
Bathroom
Car
Landsize
BuildingArea
Encoded categorical variables (Method, SellerG, CouncilArea)
Next Steps & Possible Improvements:
Feature Engineering: Add new meaningful features like Price per Square Meter.
Advanced Models: Try Random Forest, XGBoost, or Neural Networks for better accuracy.
Hyperparameter Tuning: Optimize the model using GridSearchCV or RandomizedSearchCV.
Data Visualization: Perform exploratory data analysis (EDA) using matplotlib and seaborn to understand trends better.
