Project Title:
Linear Regression Model for Predicting Airbnb Listing Prices

Description:
This project aims to predict the price of Airbnb listings using a linear regression model. It involves data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.
Dependencies:

Python 3.x
Libraries: NumPy, pandas, matplotlib, scikit-learn

Installation:
Ensure you have Python 3.x installed.
Install required libraries using pip:
Copy code
pip install numpy pandas matplotlib scikit-learn

Usage:
Clone the repository.
Run the provided Python script to execute the linear regression model for Airbnb price prediction.
NOTE : Change path of CSV file in code.

Data:

The dataset used in this project is obtained from Airbnb listings.
It contains various features about the listings such as location, amenities, property type, etc.
The target variable is the price of the listings.

Steps:

Exploratory Data Analysis: Visualized the distribution of prices and calculated statistics such as mean, median, min, max, and standard deviation.
Data Preprocessing: Removed irrelevant columns, separated target variable, and identified numerical, categorical, and binary columns.
Model Training: Used linear regression to train the model.
Model Evaluation: Evaluated the model using Root Mean Squared Error (RMSE) for both training and testing datasets.
Results:

The RMSE for the training dataset is 52.092, and for the testing dataset is 53.213.
The decision tree classifier showed overfitting with a high training accuracy (0.949) and lower testing accuracy (0.690).
Improvements:

To improve the model accuracy, feature engineering, hyperparameter tuning, or trying different algorithms could be considered.
Addressing overfitting issues by using regularization techniques or collecting more data.
