# Crop Recommendation System

## Overview
The Crop Recommendation System is a machine learning-based application designed to recommend the most suitable crop for cultivation based on the chemical and physical properties of the soil and environmental conditions. The system leverages various machine learning algorithms, with Random Forest being selected for its superior accuracy. The model is deployed using Flask, providing an accessible web interface for users.

## Features
- **Crop Recommendation**: Provides the best crop to cultivate based on soil and environmental parameters.
- **User-Friendly Interface**: The frontend is built using Flask, allowing users to input parameters and receive recommendations easily.
- **Multiple Environmental Inputs**: The model takes into account various factors, including:
  - Nitrogen levels
  - Phosphorus levels
  - Potassium levels
  - Rainfall
  - pH of the soil
  - Humidity
  - Temperature

## Technology Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask)
- **Machine Learning**:
  - Several algorithms were evaluated, including:
    - K-Nearest Neighbors (KNN)
    - Decision Trees
    - Support Vector Machine (SVM)
    - **Random Forest** (selected model)
- **Database**: CSV or any database used to store and manage the dataset (replace as per your project details)

## Machine Learning Model
- **Algorithms Explored**: The system tested several algorithms to determine the best fit for the data, including:
  - K-Nearest Neighbors (KNN)
  - Decision Trees
  - Support Vector Machine (SVM)
  - **Random Forest**: Selected for its high accuracy in predicting the best crop based on the input features.
- **Selected Model**: 
  - **Random Forest** was chosen due to its ability to handle large datasets and its high accuracy in prediction.
  - The model was trained on a dataset containing various chemical and physical properties of the soil and environmental conditions.

## Flask Application
- The application is deployed using Flask, providing an easy-to-use interface for users to input data and get crop recommendations.
- **Endpoints**:
  - `/` - Home page where users can input environmental and soil parameters.
  - `/recommend` - Processes the input and provides crop recommendations.


