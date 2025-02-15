# Credit-Card-Fraud-Detection


# Fraud Detection System

This project implements a **Credit Card fraud detection system** using machine learning techniques to classify fraudulent transactions. The dataset is preprocessed with feature engineering, resampling techniques, and supervised learning models.

## 📌 Features
- **Feature Engineering**: Time-based features, transaction frequency analysis.
- **Imbalanced Data Handling**: SMOTE (Synthetic Minority Over-sampling Technique) to balance fraud cases.
- **Machine Learning Models**: Logistic Regression, Random Forest, XGBoost, OneClasssvm
- **Precision-Recall Trade-Off**: Optimized threshold selection for fraud detection.

## 📂 Dataset
The dataset used is `creditcard.csv`, which contains anonymized transaction details. It includes:
- **Time-based attributes** (converted to hours, days).
- **Transaction amount**.
- **Binary fraud labels (0: Non-Fraud, 1: Fraud).**

## 🚀 Installation
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/FraudDetection.git
   cd FraudDetection
