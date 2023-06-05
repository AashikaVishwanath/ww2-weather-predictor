# WW2 Weather Predictor
This repository contains the code for a World War II (WW2) weather predictor. The goal of this project is to predict the maximum temperature based on the minimum temperature using a linear regression model.

## Dataset
The dataset used for this project is named "Summary of Weather" and is stored in the file "Summary of Weather.csv". It contains historical weather data including minimum and maximum temperatures.

## Installation
To run this weather predictor, follow these steps:

Clone the repository: git clone https://github.com/your-username/ww2-weather-predictor.git
Ensure you have the required dependencies installed, including numpy, matplotlib, and pandas.
Open the script.py file in a Python IDE or editor.
Execute the script to see the predicted maximum temperature based on the provided minimum temperature.

## Usage
Load the dataset using the pd.read_csv() function and extract the relevant columns for X (minimum temperature) and y (maximum temperature).
Split the dataset into training and testing sets using the train_test_split() function from scikit-learn.
Create a linear regression model using LinearRegression() from scikit-learn and fit it to the training data.
Predict the maximum temperature for the test data using the predict() function.
Visualize the results by plotting the training and test data points along with the regression line.

Kaggle dataset: https://www.kaggle.com/smid80/weatherww2
