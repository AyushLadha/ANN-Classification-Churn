# ANN-Classification-Churn

Project Overview:
This repository contains all the necessary files and models for a churn prediction project aimed at identifying customers likely to leave a bank. The project leverages an artificial neural network to classify customers based on their likelihood to churn. Using historical data, the model predicts whether a customer will exit based on features like credit score, geography, gender, and more.

Repository Structure:
Churn_Modelling.csv - The dataset used for training the model, containing customer attributes and churn status.
.ipynb - Jupyter notebook containing the exploratory data analysis, model training and validation.
model.h5 - Saved Keras model weights.
data_preprocessor.pickle - Serialized preprocessing pipeline to transform new data for predictions.
app.py - Streamlit application for deploying the model as a web app.

Data Description:
The dataset includes the following features:
CreditScore: The credit score of the customer.
Geography: The region where the customer lives.
Gender: The gender of the customer.
Age: The age of the customer.
Tenure: Number of years the customer has been with the bank.
Balance: Account balance of the customer.
NumOfProducts: Number of products the customer has with the bank.
HasCrCard: Indicates if the customer has a credit card (1 = Yes, 0 = No).
IsActiveMember: Indicates if the customer is an active member (1 = Yes, 0 = No).
EstimatedSalary: The estimated salary of the customer.
Exited: Whether the customer left the bank (1 = Yes, 0 = No - target variable).

Acknowledgments:
This project was inspired by the tutorials and teachings of Krish Naik. His detailed explanations on using artificial neural networks for churn prediction were instrumental in the development of this project. You can find his educational content on Krish Naik's YouTube channel.
