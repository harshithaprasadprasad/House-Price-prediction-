# House-Price-prediction-
A machine learning project that implements linear regression to predict house prices based on features such as square footage, number of bedrooms, and bathrooms. Includes data preprocessing, model training, evaluation, and visualization for accurate price estimation.
# Project Overview
This project implements a Linear Regression model to predict house prices based on three key features:
-> Square footage of the living area (GrLivArea)
-> Number of bedrooms above ground (BedroomAbvGr)
-> Number of full bathrooms (FullBath)

The dataset is taken from the Kaggle House Prices - Advanced Regression Techniques competition.
The goal is to build a simple but effective regression model that can estimate housing prices using basic features.

# Dataset Description

Source: Kaggle - House Prices
File Used: train.csv
Key Features Selected:
GrLivArea: Above ground living area (square feet)
BedroomAbvGr: Number of bedrooms above ground
FullBath: Number of full bathrooms
Target Variable:
SalePrice: Price of the house in USD

# Workflow & Methodology
Data Upload – Load the dataset (train.csv) into Colab or local environment.
Data Preprocessing – Select important features (GrLivArea, BedroomAbvGr, FullBath).
Train-Test Split – Split dataset into 80% training and 20% testing.
Model Training – Train a Linear Regression model on training data.
Prediction – Predict house prices for test data.
Evaluation – Evaluate model performance using:
Root Mean Squared Error (RMSE)
R² Score (coefficient of determination)
Visualization – Plot actual vs predicted prices and correlation heatmap.
Export Results – Save predictions into a CSV file for further analysis.

# Installation
To run this project in Google Colab or locally:
pip install pandas numpy matplotlib seaborn scikit-learn

# How to Run the Project
Clone the repository:
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
Upload the Kaggle dataset (train.csv) to your project folder.
Run the notebook (house_price_prediction.ipynb) in Google Colab or Jupyter Notebook.
The script will:
Train the Linear Regression model
Show model coefficients and evaluation metrics
Save predictions in predictions.csv

# File Structure
house-price-prediction/
│── house_price_prediction.ipynb   # Main notebook
│── train.csv                      # Kaggle dataset (not included in repo, upload separately)
│── predictions.csv                # Output predictions file
│── README.md                      # Project documentation
│── requirements.txt               # Python dependencies

# Sample Prediction

Example: Predicting price for a house with

2500 sqft living area

4 bedrooms

3 bathrooms

example_house = [[2500, 4, 3]]
predicted_price = model.predict(example_house)
print("Predicted Price:", predicted_price[0])
Output:
Predicted Price: $245,672.34

# Developed By

HARSHITHA PRASAD S G
GITHUB:harshithaprasadprasad
LINKEDIN: https://www.linkedin.com/in/harshitha-prasad-s-g-55a05a257
