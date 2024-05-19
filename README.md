# Multiple Linear Regression: Implementation with scikit-learn and from Scratch

** Introduction **
This repository provides an implementation of multiple linear regression using two approaches:

scikit-learn: Utilizing the LinearRegression class from the scikit-learn library, a powerful and easy-to-use machine learning framework in Python.
From Scratch: Implementing multiple linear regression algorithm manually, without relying on external libraries, to understand the underlying concepts and mathematics.
Dataset
We use a sample dataset containing features related to house prices. The dataset includes multiple features such as the area of the house, number of bedrooms, number of bathrooms, and so on, with the target variable being the price of the house.

Implementation
Using scikit-learn:
Data Preprocessing:

Load the dataset using pandas.
Split the dataset into independent features (X) and dependent variable (y).
Perform any necessary preprocessing steps like feature scaling or handling missing values.
Model Training:

Import LinearRegression from scikit-learn.
Initialize a LinearRegression model.
Fit the model to the training data (X_train, y_train) using the fit method.
Model Evaluation:

Predict the target variable for the test set (X_test) using the predict method.
Evaluate the model performance using metrics like mean squared error, R-squared, etc.
From Scratch:
Data Preprocessing:

Similar to scikit-learn, load and preprocess the dataset.
Model Training:

Implement a class for multiple linear regression.
Define methods for forward pass (prediction), weight update, training, testing, and plotting loss.
Train the model using the training data.
Model Evaluation:

Test the trained model on the test set.
Compare the performance metrics with the scikit-learn implementation.
Results
The repository provides scripts and Jupyter notebooks demonstrating both implementations. Results, including model performance metrics and visualizations, are included in the notebooks.

Dependencies
Python 3.x
NumPy
pandas
scikit-learn
