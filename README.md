# CVD_HEALTH_PREDICTION

# 🏥 General Health Prediction using Machine Learning 

## 📌 Project Overview

This project focuses on predicting a person's **General Health Status** using Machine Learning models trained on a cardiovascular disease (CVD) dataset.

The objective is to build, evaluate, and compare multiple classification models and determine the best-performing algorithm for health prediction.

---

## 🎯 Project Objectives

- Perform data preprocessing and encoding
- Split dataset into 80% training and 20% testing sets
- Build and compare three classification models:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
- Evaluate models using:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix
- Compare model performances using a bar chart
- Apply **RandomizedSearchCV** for hyperparameter tuning
- Simulate an AI system with single-input prediction

---

## 📊 Dataset Description

The dataset contains demographic and health-related attributes such as:

- Age Category
- Gender
- BMI
- Smoking
- Physical Activity
- Diabetes
- Heart Disease
- And other health indicators

**Target Variable:** `General_Health`  
(Categorical health levels such as Poor, Fair, Good, Very Good, Excellent)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 🔍 Machine Learning Models Implemented

### 1️⃣ Logistic Regression
- Baseline linear classification model
- Fast and interpretable

### 2️⃣ Random Forest
- Ensemble learning method
- Handles structured health data effectively
- Provided the best overall performance

### 3️⃣ Support Vector Machine (SVM)
- Effective classifier for structured data
- Trained on sampled data for computational efficiency

---

## 📈 Model Evaluation Metrics

Each model was evaluated using:

- Accuracy Score
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix

A comparison bar chart was plotted to visually compare model performances.

## ⚙️ Hyperparameter Tuning

RandomizedSearchCV was applied to the best-performing model (Random Forest) to optimize:

- Number of estimators
- Maximum depth
- Minimum samples split
- Minimum samples leaf

This improved the final prediction accuracy.

---

## 🤖 AI System Simulation

The project includes:

- Single sample prediction from dataset
- Custom user input prediction system

This simulates how a real-world AI-based health prediction system works.

---

## 🏆 Final Conclusion

Among the implemented models, **Random Forest achieved the best performance** for predicting General Health status.

Hyperparameter tuning further enhanced model performance, making it the most suitable model for deployment in real-world health prediction systems.

---

## 📂 Project Structure

CVD_HEALTH_PREDICTION/
│
├── CVD_cleaned.csv
├── CVD_Health_Prediction.ipynb
└── README.md
