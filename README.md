# Smart Home Energy Prediction

This project focuses on predicting household energy consumption using machine learning techniques.
The model is trained and executed on an AWS EC2 instance as part of the course project requirements.

## Project Scope
The goal of this project is to predict **Global Active Power** consumption of a household
based on electrical measurements such as voltage and current intensity.

## Dataset
- **Name:** Household Power Consumption Dataset  
- **Source:** UCI Machine Learning Repository  
- **File:** `data/raw/household_power_consumption.csv`

## Features and Target
- **Input Features:**
  - Voltage
  - Global_intensity
- **Target Variable:**
  - Global_active_power

## Model
- **Algorithm:** Linear Regression
- **Library:** scikit-learn
- **Evaluation Metric:** R² Score

## AWS EC2 Deployment
The entire workflow was executed on an AWS EC2 instance:
- Python environment setup
- Dataset transfer via SCP
- Model training and evaluation on EC2
- Results pushed to GitHub from the EC2 instance

## Repository Structure
dashboards/
data/
└── raw/
└── household_power_consumption.csv
docs/
models/
notebooks/
src/
README.md

## Results
The trained model achieved a high R² score, indicating strong predictive performance on the test dataset.

## Author
Umut Murathan Kılıç  
GitHub: https://github.com/umutklc2000
