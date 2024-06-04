# California House Price Prediction

This project uses a machine learning model to predict house prices in California based on various features like median income, house age, average rooms, average bedrooms, population, average occupancy, latitude, and longitude.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [License](#license)

## Overview
The California House Price Prediction project utilizes a linear regression model trained on the California housing dataset to predict the prices of houses. This project includes a Flask web application where users can input the required features to get the predicted house price.

##Installation:
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/california-house-price-prediction.git
   cd california-house-price-prediction
python -m venv venv

## 2.Create and activate a virtual environment:
venv\Scripts\activate

## 3.Install the dependencies:
pip install -r requirements.txt

## 4.Usage
To start the Flask web application, run:
python app.py

## 5.Project Structure
california-house-price-prediction/
│
├── venv/                    # Virtual environment directory
├── templates/
│   └── home.html            # HTML file for the web application
├── .gitignore
├── app.py                   # Flask application
├── california_house_price.ipynb  # Jupyter notebook for data analysis and model training
├── LICENSE
├── README.md                # Project readme file
├── regmodel.pkl             # Serialized trained model
├── requirements.txt         # Project dependencies


## 6.Features:
Predict house prices based on user input features.
Simple and user-friendly web interface built with Flask.
Model trained on the California housing dataset.

## 7.Deployment LInk:
https://california-house-price-3.onrender.com/
