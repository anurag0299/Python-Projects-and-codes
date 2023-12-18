# Stock Price Prediction using GRU

This Python script implements a stock price prediction model using a Gated Recurrent Unit (GRU) neural network. The dataset used contains daily stock prices for various companies.

## Usage

1. Ensure you have the necessary libraries installed:

Download the dataset prices-split-adjusted.csv and place it in the same directory as the script.
Dataset Link : https://www.kaggle.com/datasets/dgawlik/nyse?select=prices-split-adjusted.csv
Run the script:

Description
Data Loading: Loading stock price dataset and exploring basic statistics.
Data Preprocessing: Handling missing values, converting date to datetime, and filtering data for a specific stock (Yahoo in this case).
Holiday Identification: Identifying holidays and filling missing values accordingly.
Plotting Function: A function to visualize stock prices over time.
Data Splitting: Dividing the dataset into training, validation, and test sets.
Model Creation: Building and training a GRU-based model using TensorFlow/Keras.
Model Evaluation: Assessing the performance of the model on training, validation, and test sets.
Visualizing Predictions: Plotting actual vs. predicted stock prices.
Model Scoring: Calculating Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).
Training History Plot: Displaying the loss during training and validation.