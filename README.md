# Wine Quality Prediction - End-to-End Data Science Project

This project predicts the quality of wine based on various features such as acidity, sulfur content, pH, alcohol content, etc. The model is trained using **ElasticNet** regression and deployed as a **Flask web application**. 

The project utilizes **Dagshub** for version control and experiment tracking, and **MLflow** for model tracking and registry.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
  - [Prerequisites](#prerequisites)
  - [Project Structure](#project-structure)
  - [Installing Dependencies](#installing-dependencies)
- [Model Training](#model-training)
- [Running the Flask App](#running-the-flask-app)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project involves training a machine learning model to predict the quality of wine based on various chemical properties such as acidity, sulfur content, and alcohol levels. After training the model, a **Flask** web application is used to take user input and return a prediction of the wine's quality.

The project consists of the following stages:
1. **Data Preprocessing and Model Training**: Using **ElasticNet** regression to train a predictive model.
2. **Model Logging and Experiment Tracking**: Using **MLflow** and **Dagshub** for model versioning and tracking.
3. **Flask Web Application**: A simple web interface where users can input features of wine and get predictions.

## Technologies Used

- **Python**
- **Flask**: For the web application.
- **ElasticNet Regression**: For wine quality prediction.
- **MLflow**: For model versioning and experiment tracking.
- **Dagshub**: For managing and tracking model versions.
- **HTML/CSS**: For frontend design of the Flask web app.
- **Pandas, Numpy, Scikit-learn**: For data processing and machine learning.

## Setup and Installation

### Prerequisites

Before starting, ensure that you have **Python 3.x** installed and the following libraries:

- Flask
- scikit-learn
- pandas
- numpy
- mlflow
- joblib
- dagshub
- matplotlib

### Installing Dependencies

1. Clone the repository:
    git clone https://github.com/your-username/wine-quality-prediction.git

2. Install required dependencies:
    pip install -r requirements.txt


## How to Use

### **Model Training**:
1. First, run `main.py` to train the **ElasticNet** model. This will generate a trained model file (`model.pkl`).
   
   To train the model, run the following command:
   ```bash
   python main.py

### **Flask App**:
1. After training the model, run `app.py` to launch the **Flask app**.
   
   To start the Flask app, run the following command:
   ```bash
   python app.py

