Voyage-Analytics-Integrating-MLOps-in-Travel-Productionization-of-ML-Systems
Overview
This repository contains a comprehensive solution for a multi-task machine learning project, including gender classification, hotel recommendation, and price prediction models. The models have been trained on an extensive dataset and are available for inference via Docker images. Additionally, the prediction models are hosted and accessible via a shared link on Google Drive.

Dataset
The dataset used in this project encompasses multiple aspects:

Gender Classification: Features that contribute to predicting the gender of a user, which may include demographics and user preferences.
Hotel Recommendation: Data related to user preferences, past bookings, and ratings, utilized for suggesting hotels.
Price Prediction: A model that predicts the price of hotel bookings based on various factors, including time of booking, location, and demand.
Models
1. Gender Classification Model
Task: Classify the gender of users based on available features.
Model Type: Classification
Performance Metrics: Accuracy, Precision, Recall, F1-Score
2. Hotel Recommendation Model
Task: Recommend hotels to users based on past preferences and behavioral data.
Model Type: Recommendation System
Performance Metrics: Precision@K, Recall@K, Mean Average Precision (MAP)
3. Price Prediction Model
Task: Predict the price of hotel bookings.
Model Type: Regression
Performance Metrics: Mean Squared Error (MSE), Mean Absolute Error (MAE), R² Score
