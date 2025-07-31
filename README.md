Title: Weather Data Analysis and Temperature Prediction Using Linear Regression

Project Overview:

This project focuses on analyzing historical weather data to build a machine learning model that predicts future minimum temperatures. It introduces the concept of time series data analysis and applies feature engineering and regression techniques. The project is implemented using Python in Google Colab.

Objectives:

Load and explore historical weather data containing daily minimum temperatures.

Perform data preprocessing such as date conversion and feature creation.

Visualize temperature trends using line graphs.

Build a linear regression model using previous day temperature as the feature.

Evaluate the model using error metrics like Mean Absolute Error and Root Mean Square Error.

Predict future temperatures and display them visually along with historical data.

Dataset Used:

Source: Daily Minimum Temperatures Dataset from a public GitHub repository
Attributes:

Date: The date of observation.

Temp: The minimum daily temperature in Celsius.

Technologies and Tools:

Programming Language: Python
Development Environment: Google Colab
Libraries Used:

pandas for data handling

matplotlib and seaborn for data visualization

scikit-learn for building and evaluating the regression model

numpy for numerical operations

Model Summary:

A simple linear regression model was trained to predict the current day's temperature based on the previous day's temperature. The model was evaluated using standard metrics and showed reasonable accuracy for short-term predictions. The final model was also used to predict temperatures for the next seven days.

Conclusion:

This project demonstrates how to handle time series data and use basic regression for forecasting. It provides a strong foundation for further improvements, such as using seasonal features or more advanced time series models like ARIMA or LSTM.# weather-prediction-
