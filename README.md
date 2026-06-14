# Credit-Card-Fraud-Detection-Using-Autoencoders
Project Overview

This project implements a Deep Autoencoder-based anomaly detection system for identifying fraudulent credit card transactions. The model is trained using legitimate transactions and detects fraud based on reconstruction error.

Dataset

Dataset: Credit Card Fraud Detection Dataset

Source: Kaggle

The dataset contains 284,807 transactions, including 492 fraudulent transactions.

Algorithm Used

Deep Autoencoder

The Autoencoder learns normal transaction patterns and identifies anomalies using reconstruction error.

Technologies Used
Python
TensorFlow
Keras
NumPy
Pandas
Matplotlib
Scikit-Learn
Model Architecture

Input Layer (29 Features)

↓

Dense Layer (16 Neurons)

↓

Dense Layer (8 Neurons)

↓

Dense Layer (16 Neurons)

↓

Output Layer (29 Features)

Results
Average Reconstruction Error (Normal): 0.2804
Threshold: 0.6844
Average Reconstruction Error (Fraud): 18.6894
Frauds Detected: 437 / 492
Detection Rate: 88.82%
Conclusion

The Deep Autoencoder successfully learned normal transaction behavior and detected fraudulent transactions through anomaly detection techniques, achieving a fraud detection rate of approximately 88.8%.
