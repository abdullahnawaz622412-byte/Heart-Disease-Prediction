# ❤️ Heart Disease Prediction using Decision Tree, Random Forest & XGBoost

## 📌 Overview

This project compares three popular machine learning algorithms for predicting whether a patient has heart disease based on medical information.

The objective of this project was not only to build a predictive model, but also to compare different tree-based algorithms and understand how hyperparameter tuning can improve model performance.

---

## 📂 Dataset

**Heart Disease Dataset**

The dataset contains patient health information such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- ST Depression
- Slope
- Number of Major Vessels
- Thalassemia

**Target Variable**

- 0 → No Heart Disease
- 1 → Heart Disease

---

## 🎯 Objective

The goal of this project is to predict whether a patient has heart disease using multiple machine learning algorithms and compare their performance.

---

## 🛠️ Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn
- xgboost
- jupyter

---

## 📚 Concepts Practiced

- Decision Trees
- Random Forest
- XGBoost
- One-Hot Encoding
- Train/Test Split
- Hyperparameter Tuning
- GridSearchCV
- Model Comparison
- Feature Importance
- Classification

---

## 🔄 Project Workflow

### 1. Import Libraries

Import all required libraries for data manipulation, visualization, and machine learning.

---

### 2. Load & Explore the Dataset

- Load the dataset
- Inspect the data
- View dataset shape
- Check data types
- Generate summary statistics
- Check for missing values

---

### 3. Data Preprocessing

- Handle categorical features using One-Hot Encoding
- Convert categorical variables into numerical format
- Prepare the dataset for machine learning algorithms

---

### 4. Split the Dataset

Split the data into:

- Training Set
- Testing Set

The training set is used to train the models, while the testing set is used to evaluate their performance.

---

### 5. Train a Decision Tree

Build and train a Decision Tree classifier.

Experiment with hyperparameters such as:

- Maximum Depth
- Minimum Samples Split

Evaluate the model's accuracy.

---

### 6. Train a Random Forest

Build a Random Forest classifier using multiple decision trees.

Tune important hyperparameters using **GridSearchCV**, including:

- Number of Estimators
- Maximum Depth
- Minimum Samples Split

Evaluate the optimized model.

---

### 7. Train an XGBoost Model

Train an XGBoost classifier and compare its performance with the previous models.

---

### 8. Compare Model Performance

Compare all three algorithms based on their prediction accuracy and identify which model performs best on the dataset.

---

### 9. Analyze Feature Importance

Visualize feature importance to understand which medical attributes contributed most to the model's predictions.

---

## 📈 Results

Three tree-based machine learning models were successfully trained and evaluated:

- Decision Tree
- Random Forest
- XGBoost

The project demonstrates how ensemble methods such as Random Forest and XGBoost can improve prediction performance compared to a single Decision Tree.

---

## 📁 Project Structure

```
Heart-Disease-Prediction/
│
├── Heart_Disease_Prediction.ipynb
├── heart.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Future Improvements

- Perform cross-validation for more reliable evaluation
- Experiment with additional hyperparameters
- Compare with Logistic Regression and Support Vector Machines (SVM)
- Use feature selection techniques
- Deploy the trained model as a simple web application using Streamlit or Flask

---

## 👨‍💻 Author

**Abdullah Nawaz**

This project is part of my Machine Learning & Deep Learning learning roadmap, where I build practical projects to strengthen my understanding of machine learning algorithms through hands-on implementation and model comparison.
