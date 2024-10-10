# Predicting House Prices Using Linear Regression
This project focuses on predicting house prices using a simple linear regression model. The dataset includes features such as the number of bedrooms, bathrooms, and square footage to estimate the price of a house.
# Dataset
The dataset should include the following columns:

bedrooms: Number of bedrooms in the house.
bathrooms: Number of bathrooms in the house.
square_footage: Total square footage of the house.
price: The target variable representing the price of the house.

# Project Workflow
Data Loading:

Load the dataset using pandas and display its structure to understand the features.

Feature Selection:

Select the relevant features (independent variables) for predicting house prices, such as bedrooms, bathrooms, and square_footage.
The target variable is price, which represents the house prices.

Data Splitting:

Split the data into training and test sets using an 80/20 split to train the model and evaluate its performance on unseen data.

Modeling:

Use the LinearRegression model from Scikit-learn to predict house prices based on the selected features.
Train the model on the training set, and then make predictions on the test set.

Evaluation:

Use Mean Squared Error (MSE) to measure the accuracy of the model. A lower MSE indicates better performance.
Visualize the results by plotting actual vs. predicted house prices to understand how well the model performs.

Visualization:

A scatter plot is generated to visualize how well the model's predicted values align with the actual prices.
