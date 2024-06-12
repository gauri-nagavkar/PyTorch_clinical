
# Heart Disease Prediction using Deep Learning

## Introduction

This project aims to predict heart disease using clinical data from the UCI Machine Learning Repository. We implement and compare the performance of various deep learning models, including a Multi-layer Perceptron (MLP), a Convolutional Neural Network (CNN), and a Recurrent Neural Network (RNN).

## Dataset

### Citation

Janosi, Andras, Steinbrunn, William, Pfisterer, Matthias, and Detrano, Robert. (1988). Heart Disease. UCI Machine Learning Repository. https://doi.org/10.24432/C52P4X.

The dataset contains 14 features and 303 instances. The features include:

- Age
- Sex
- Chest pain type (cp)
- Resting blood pressure (trestbps)
- Serum cholesterol (chol)
- Fasting blood sugar (fbs)
- Resting electrocardiographic results (restecg)
- Maximum heart rate achieved (thalach)
- Exercise-induced angina (exang)
- ST depression induced by exercise relative to rest (oldpeak)
- Slope of the peak exercise ST segment (slope)
- Number of major vessels colored by fluoroscopy (ca)
- Thalassemia (thal)

The target variable (`num`) indicates the presence or absence of heart disease.

## Methods

### Data Preprocessing

1. Handle missing values
2. Normalize the data

### Exploratory Data Analysis (EDA)

1. Pair plots to visualize relationships between features and the target variable
2. Correlation heatmap

### Model Development

1. Multi-layer Perceptron (MLP)
2. Convolutional Neural Network (CNN)
3. Recurrent Neural Network (RNN)

### Model Evaluation

Evaluate model performance using various metrics and visualizations, including accuracy, precision, recall, F1 score, ROC-AUC score, confusion matrix, and ROC curve.

## File Structure

- `Heart_Disease_Prediction_Project.ipynb`: Jupyter notebook containing the project code and analysis.
- `README.md`: This file.

## Conclusion

This project demonstrates the application of various deep learning models to predict heart disease using clinical data. Each model's performance is evaluated, showing their strengths and areas for improvement.
