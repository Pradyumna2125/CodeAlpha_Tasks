# CodeAlpha Machine Learning Internship Projects

## Internship
**Organization:** CodeAlpha  
**Domain:** Machine Learning  
**Internship Type:** Online  
**Duration:** As per CodeAlpha guidelines  

This repository contains projects completed as part of the **CodeAlpha Machine Learning Internship**, fulfilling the assigned tasks within the given time frame.

---

## Project 1: Handwritten Character Recognition (A–Z)

### Description
This project implements a **Handwritten Character Recognition system** that identifies English alphabet characters (A–Z) from handwritten images using a **Convolutional Neural Network (CNN)**.

### Dataset
**EMNIST Letters Dataset**
- Official: https://www.nist.gov/itl/products-and-services/emnist-dataset  
- Kaggle: https://www.kaggle.com/datasets/crawford/emnist  

### Model Details
- Framework: TensorFlow / Keras
- Input: 28×28 grayscale images
- Output: 26 character classes (A–Z)
- Model Type: CNN

### Output File
- `handwritten_character_recognition_AZ.h5`

---

## Project 2: Credit Scoring Model

### Description
This project predicts **credit risk (Good / Bad)** for customers using financial and personal attributes.  
It follows a **classical machine learning approach** commonly used in the banking and finance industry.

### Dataset
**German Credit Dataset**
- Kaggle: https://www.kaggle.com/datasets/uciml/german-credit  
- Original (UCI): https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)

### Model Details
- Algorithm: Logistic Regression
- Preprocessing: StandardScaler, categorical encoding
- Evaluation: Accuracy, ROC-AUC

### Output Files
- `credit_model.pkl`
- `scaler.pkl`

---

## How to Run the Projects

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
