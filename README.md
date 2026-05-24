# Multimodal ML – Housing Price Prediction

## Objective
The objective of this project is to predict housing prices using both:
- Structured tabular data
- Image data

This project demonstrates multimodal machine learning by combining CNN-extracted image features with tabular housing features.



# Dataset
Dataset used:
- Jiffs Housing Dataset

Dataset contains:
- Housing attributes
- Property prices
- House-related features



# Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- Scikit-learn
- Pandas
- NumPy
- Matplotlib



# Methodology

## 1. Data Preprocessing
- Removed missing values
- Selected important housing features
- Normalized tabular data

## 2. Image Processing
- CNN feature extraction using MobileNetV2
- Image resizing and normalization

## 3. Multimodal Learning
- Combined:
  - CNN image features
  - Tabular features

using feature fusion.

## 4. Regression Modeling
- Built deep learning regression model
- Predicted property values



# Evaluation Metrics

## Mean Absolute Error (MAE)

MAE measures average prediction error.

## Root Mean Squared Error (RMSE)

RMSE penalizes larger prediction errors.


# Results
The multimodal model successfully combined image and tabular features for housing price prediction.

Outputs included:
- Training loss graph
- Actual vs Predicted graph
- MAE
- RMSE


