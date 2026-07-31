# AI Applications for Prediction and Computer Vision

Deep Learning | Neural Networks | Computer Vision | Python

## Overview

This project explores two practical applications of Artificial Intelligence using deep learning techniques.

The first task develops neural network models to predict residential property prices based on housing characteristics. The second task investigates image classification using Artificial Neural Networks (ANNs) and Convolutional Neural Networks (CNNs) for automated waste sorting.

Together, these projects demonstrate the application of AI to both structured tabular data and unstructured image data.

---

## Project 1 — House Price Prediction

### Business Problem

Accurate property valuation supports informed decision-making for buyers, sellers, and real estate professionals. This project investigates how different neural network architectures affect prediction accuracy for house prices.

### Methodology

- Data Cleaning and Preprocessing
- Outlier Removal
- Feature Normalisation
- Multiple Neural Network Architectures
- Model Evaluation using:
  - MAE
  - RMSE
  - MAPE
  - Correlation
  - R²

### Key Results

- Developed and compared eight prediction models.
- Three-layer neural networks achieved the strongest predictive performance.
- The best model (NN4) achieved:
  - Correlation: **0.919**
  - R²: **0.845**
  - MAE: **$71,705**
- Increasing model complexity beyond three hidden layers did not improve performance.

---

## Project 2 — Waste Image Classification

### Business Problem

Automated waste classification can improve recycling efficiency and reduce manual sorting. This project evaluates different deep learning architectures for classifying waste images into six categories.

### Methodology

- Image Preprocessing
- Data Normalisation
- Artificial Neural Networks (ANN)
- Convolutional Neural Networks (CNN)
- Performance Evaluation using:
  - Accuracy
  - Cohen's Kappa
  - Precision
  - Recall
  - F1-score

### Key Results

- Compared four ANN models and six CNN models.
- CNN models significantly outperformed ANN models.
- The best model (CNN4) achieved:
  - Test Accuracy: **69.53%**
  - Cohen's Kappa: **0.631**
- Vegetation images were classified most accurately, while plastic and metal remained the most challenging categories.

---

## Technologies

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Skills Demonstrated

- Data Preprocessing
- Feature Engineering
- Neural Networks
- Deep Learning
- Computer Vision
- Model Evaluation
- Hyperparameter Tuning
- Business Analytics
- AI Model Comparison

---

## Author

**Huong Linh Vu**

Bachelor of Business Analytics

Deakin University
