##🚗 EV Charging Station Availability Predictor (Supervised Learning)

This project builds a simple machine learning model that recommends the best EV charging station based on:
Charging slots availability,
Distance to station
Time of day and day of week
Vehicle type
Weather temperature


We simulate user and station data, train a regression model to predict the number of available charging slots, and recommend the best station based on predicted availability and proximity.
This is one feature of a proposed mobile app that recommends charging stations to Electric Vehicles. 


✅ What the Notebook Does
Simulates training data
 Randomly generates 500 data points with distance, time, weather, and vehicle type.
Trains a model
 Uses a Random Forest Regressor to predict number of available slots.
Predicts and recommends
 Given a user’s location and context, predicts station availability and recommends the best options.

📌 Features
Supervised learning (regression)
Feature encoding for categorical data
Distance calculation using geodesic coordinates
Prediction-based station ranking

🔧 Requirements
All libraries are included in Google Colab:
pandas
numpy
scikit-learn
geopy


🚀 How to Use
Run script in order to simulate data, train the model, and view recommendations
Update user location or station list to test various scenarios


## Mobile App pitch deck

## Mobile App blog
