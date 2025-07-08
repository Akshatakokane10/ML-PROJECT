# ML-PROJECT
# 🩺 Diabetes Prediction Web App

A web-based machine learning application built using Flask to predict whether a person is likely to have diabetes based on input health parameters. The model is trained on the [kaggle_diabetes.csv](dataset/kaggle_diabetes.csv) dataset.

## 🚀 Features

- User-friendly interface for diabetes prediction
- Accepts health data like BMI, Glucose, Blood Pressure, etc.
- Built using Python, Flask, HTML/CSS
- Trained using a classification ML algorithm
- Deployed-ready with `Procfile` and `requirements.txt`

## 📁 Project Structure
├── dataset
│ └── kaggle_diabetes.csv # Dataset for training the model
├── Diabetes-prediction-d # Main project directory
│ ├── Resource/ # Any utility resources
│ ├── static/ # CSS, JS, image files
│ ├── templates/ # HTML templates
│ ├── app.py # Flask backend server
│ ├── Diabetes Predictor - ... # Possibly Jupyter notebook or model script
│ ├── diabetes-prediction-... # Another relevant script/notebook
│ ├── requirements.txt # Python dependencies
│ ├── Procfile # For deployment (e.g., Heroku)
│ ├── Diabetes Classification... # Model training or report
│ └── README.md # This file

## 📊 Dataset Info

- Dataset: `kaggle_diabetes.csv`
- Source: [Kaggle Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Features used:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age

