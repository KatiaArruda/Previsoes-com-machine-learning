# Credit Score Analysis and Prediction

This project aims to analyze and predict the credit score of clients using Machine Learning algorithms. For this purpose, we used a dataset containing financial information of the clients and applied machine learning techniques for classification.

# Technologies Used

Language: Python

Libraries: Pandas, Scikit-Learn, Matplotlib

Machine Learning Models: Random Forest and K-Nearest Neighbors (KNN)

# Project Structure

# Data Reading and Exploration

- The data is loaded from a CSV file (clientes.csv).

- The DataFrame structure is displayed to understand the columns.

 # Data Preprocessing

- Conversion of categorical variables into numerical with LabelEncoder.

- Definition of the target variable (score_credito) and the predictor variables.

- Splitting the data into training and testing sets.

# Model Training

- Using Random Forest and KNN models for training.

- Fitting the models to the training data.

  Validation and Evaluation

# Prediction of test values.

Calculating accuracy for each model:

- Random Forest: 82.61%

- KNN: 73.24%

# Prediction for New Clients

- Loading new data (novos_clientes.csv).

- Applying the trained model to predict credit scores.

 # Results Visualization

Graph showing the distribution of client credit scores.

# Results Analysis

The models show good performance in predicting the credit score, with the Random Forest being the most accurate. This project can be expanded with model optimization and the inclusion of new variables to improve prediction.
