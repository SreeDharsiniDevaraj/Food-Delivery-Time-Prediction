# Food-Delivery-Time-Prediction using LSTM Neural Network Model

## Overview

This project aims to predict the food delivery time of various food delivery services like Swiggy and Zomato based on Machine Learning.

## Dataset

The dataset, sourced from Kaggle's Food Delivery Time Prediction dataset, includes the various Order Delivery information, Restaurant Location, Order type, Type of vehicle used to deliver the order, Type of food delivered and Time taken to reach the delivery location.

## Requirements

- pandas
- numpy
- matplotlib
- plotly
- scikit-learn
- tensorflow

## Process

1. Start with downloading the deliverytime dataset from the repository
2. Install the required libraries in Jupyter Notebook
3. Check for any inconsistencies, missing or null values and outliers in the data
4. Calculate the distance between the food preparation point and the point of food consumption.
5. Find the relationships between the time taken by delivery partners to deliver the food in the past for the calculated Distance, Delivery Person Age, Delivery Person Ratings, Type of vehicle used and the Type of food delivered through visualizations
6. Find the features that most-affect the delivery time and train the model using LSTM Neural Network
7. Predict the Time-taken by giving the required inputs
