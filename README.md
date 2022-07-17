# Supervised Machine Learning - House Price Prediction

## Introduction
This project is divided into two parts. The first part utilizes classification algorithms to classify houses as expensive or not expensive. The second part utilizes regression algorithms to predict the exact price of the house.

## Description
For the classification problem, a dataset with only numerical features are provided for initial data exploration to gain insights. A simple decision tree model is then built for a rough prediction. Later iterations of the dataset contains additional numerical and categorical features. Pipelines with imputer, categorical encoders, scalers and grid search with cross validation are then built to process the input data and tune the hyperparameters for more precise predictions. 

For the regression problem, feature selection have been done to eliminate features that contain mostly null value, are highly correlated, have low variance and have low correlation with the target. PCA is also done for dimensionality reduction. 

The following algorithms have been used for classification and/or price predictions
- Linear Regression
- Decision Tree
- K-Nearest Neighbors
- Logistic Regression
- Support-Vector Machine
- Random Forest

The following metrics have been used to evaluate the prediction results
- Accuracy Score
- Confusion Matrix
- Mean Squared Error
- Mean Absolute Error
- $R^2$

A webapp is built using Streamlit such that users can input their own parameter values and get a price prediction for the house.<br>
https://presthisbutton-house-price-predictio-knn-model-streamlit-ze9try.streamlitapp.com/

## Tools
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle
- Streamlit
