# Health Risk Prediction System

## Overview
This project uses Machine Learning techniques to predict a patient's health risk level based on vital signs and clinical parameters.

## Dataset Features
- Respiratory Rate
- Oxygen Saturation
- O2 Scale
- Systolic Blood Pressure
- Heart Rate
- Temperature
- Consciousness Level
- On Oxygen

## Data Preprocessing
- Missing value handling
- Duplicate removal
- Data type conversion
- Label encoding

## Machine Learning Models
1. Logistic Regression
2. Random Forest
3. Decision Tree
4. Support Vector Machine (SVM)

## Model Evaluation
Models were compared using:
- Accuracy Score
- Classification Report

## Final Model
Random Forest was selected as the final predictive model.

## Deployment
A Gradio-based user interface was developed to allow users to enter patient information and receive risk predictions.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Gradio
- Google Colab

## How to Run

```bash
pip install -r requirements.txt
