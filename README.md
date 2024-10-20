# Multiple Disease Prediction System

## Overview
The **Multiple Disease Prediction System** is a machine learning-based web application that predicts the likelihood of a person having heart disease, Parkinson's disease, or diabetes. It leverages various classification algorithms to analyze user inputs and provides quick, reliable predictions.
The MDPS project employs Support Vector Machine (SVM) and Logistic Regression, a powerful machine learning algorithm, to predict multiple diseases in real-time. The project is structured into three main steps:

1.Model Training: Development of the predictive model using SVM algorithm. The model is trained on labeled data to learn patterns and relationships between input features and disease outcomes.

2.Input Acquisition: Utilization of a Kaggle data set to capture input data for prediction. This real-time input allows for seamless interaction with the model.

3.Prediction: Implementation of the prediction process using Streamlit framework. Users can give input data, and the model provides predictions on the type of disease the person may have.

## Features
- Predicts three diseases: Heart Disease, Parkinson’s Disease, and Diabetes.
- User-friendly web interface.
- Efficient and fast predictions based on user input.
- Built using Python's machine learning libraries.

## Technologies Used
- **Web Application**: Streamlit
- **Machine Learning Libraries**: scikit-learn, pandas, numpy
- **Modeling Algorithms**: Logistic Regression, SVM, Random Forest, etc.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/multiple-disease-prediction.git

## How It Works
- **Input**: The user enters various health metrics such as age, blood pressure, glucose levels, etc.
- **Model Prediction**: Based on the input, the system uses trained machine learning models to predict the likelihood of a specific disease.
- **Output**: The system provides the prediction result and advises whether further medical consultation is recommended.
