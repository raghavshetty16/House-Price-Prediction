# House-Price-Prediction-
This repository contains code for predicting housing prices using various models, including Multiple Linear Regression (MLS), Linear Regression, and Neural Network, implemented in Python.

# Dataset
The dataset used for this regression task is loaded from the 'Housing.csv' file. The dataset contains information about housing prices, including features like area, bedrooms, bathrooms, stories, parking, and more.

# Data Exploration
The code performs data exploration, including checking the dataset's shape, information, and handling any missing values. It visualizes the data distribution using box plots and density plots.

# Data Preprocessing
The preprocessing steps involve encoding categorical columns, addressing skewness using power transformation, and scaling the numerical features. The code then builds a new dataframe combining the preprocessed numerical and encoded categorical features.

# Model Building
Multiple Linear Regression (MLS)
The code builds a Multiple Linear Regression model using the Ordinary Least Squares (OLS) method. It trains the model, and the results, including coefficients and statistical information, are displayed.

 # Linear Regression
A Linear Regression model is built and trained on the scaled training data. Predictions are made on the testing data, and the Mean Squared Error (MSE) is calculated.

# Neural Network
A simple Neural Network is implemented using TensorFlow and Keras. The model is trained on the scaled training data, and predictions are made on the testing data. The MSE for the Neural Network model is calculated.

# Model Evaluation
The code makes predictions using the MLS model, Linear Regression model, and Neural Network. It calculates and displays the MSE for each model, allowing comparison of their prediction accuracy.

Feel free to explore the code for housing price prediction using Multiple Linear Regression, Linear Regression, and Neural Network models!

# Usage
Ensure you have the necessary dependencies installed:

pandas      
numpy              
seaborn                            
matplotlib                           
statsmodels                                   
scikit-learn                                
tensorflow                          


Run the code to load the dataset, perform data exploration, preprocess the data, and build/train the models.

Explore the results and model evaluation metrics.

# Note
Make sure to have the 'Housing.csv' file in the same directory as the code for successful execution.
