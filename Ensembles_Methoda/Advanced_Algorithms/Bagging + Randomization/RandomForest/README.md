# ☕ Coffee Quality Classification using Ensemble Machine Learning

## 🚀 Project Overview

This project builds a Machine Learning model that predicts whether a coffee sample is **Good Quality** or **Bad Quality** using sensory evaluation scores.

The system uses **Ensemble Learning techniques** such as RandomForest and Bagging to improve prediction accuracy and stability.

The project covers the complete ML workflow:

* 📥 Data loading
* 🧹 Data cleaning
* 📊 Exploratory Data Analysis
* 🔍 Feature visualization
* 🤖 Model training
* 📈 Model evaluation
* ⚖ Model comparison
* ⭐ Feature importance
* 🧪 Prediction system

This project helps in understanding how real-world quality prediction systems work.

---

## 🎯 Objective

The goal of this project is to:

* Learn Ensemble Learning algorithms
* Apply RandomForest and Bagging on real dataset
* Perform proper data analysis before training
* Compare multiple models
* Build a small prediction system

This project follows a real Machine Learning pipeline.

---

## 📊 Dataset Information

Each row in the dataset represents one coffee sample evaluated by experts.

### ✅ Features used

* Aroma
* Flavor
* Aftertaste
* Acidity
* Body
* Balance
* Uniformity
* Clean Cup
* Sweetness
* Cupper Points
* Moisture
* Category One Defects
* Category Two Defects
* Quakers

### 🎯 Target Variable

A new column called **quality** was created.

Rule used:

* ✅ Good Coffee → Total Cup Points ≥ 82
* ❌ Bad Coffee → Total Cup Points < 82

This converts the problem into **Binary Classification**.

---

## 🛠 Libraries Used

* pandas → data handling
* numpy → numerical operations
* matplotlib → plotting
* seaborn → visualization
* scikit-learn → machine learning

---

## 🔍 Exploratory Data Analysis

The following analysis was done:

* ✔ Checking missing values
* ✔ Selecting useful columns
* ✔ Handling null values
* ✔ Statistical summary
* ✔ Quality distribution plot
* ✔ Feature vs quality graphs
* ✔ Correlation heatmap

### 📊 Graphs included

* Count plot of quality
* Aroma vs Quality
* Flavor vs Quality
* Acidity vs Quality
* Body vs Quality
* Balance vs Quality
* Correlation Heatmap
* Model Comparison Plot
* Feature Importance Plot

These graphs help understand how features affect coffee quality.

---

## ⚙ Data Preprocessing

Steps performed before training:

* Removed unnecessary columns
* Filled missing values
* Created quality label
* Split features and target
* Train-test split (80 / 20)

This ensures correct model training.

---

## 🤖 Models Used

### 🌲 RandomForest Classifier

* Ensemble algorithm
* Uses multiple decision trees
* Uses random feature selection
* Reduces overfitting
* Gives high accuracy

### 📦 Bagging Classifier

* Bootstrap Aggregation
* Multiple trees on random samples
* Reduces variance
* Improves stability

Both models were trained and compared.

---

## 📈 Model Evaluation

Evaluation methods:

* Accuracy Score
* Confusion Matrix
* Classification Report

Result:

* RandomForest → High accuracy
* Bagging → High accuracy
* RandomForest slightly better

Comparison graph was created.

---

## ⭐ Feature Importance

RandomForest was used to find most important features.

Important features observed:

* Flavor
* Aroma
* Balance
* Acidity
* Cupper Points

Feature importance helps understand model behavior.

---

## 🧪 Prediction System

A prediction system was built.

Input → coffee feature values
Output → Good / Bad quality

Example output:

* ✅ Good Quality Coffee
* ❌ Bad Quality Coffee

This makes the project closer to real-world use.

---

## 📚 What I Learned

* Data cleaning techniques
* Exploratory Data Analysis
* RandomForest algorithm
* Bagging method
* Model comparison
* Feature importance
* Building prediction system

This project improved my understanding of **Ensemble Learning**.

---

## 👩‍💻 Author

Diya Patel
🎓 BCA Student
🤖 Machine Learning Enthusiast
📊 Interested in AI, Data Science, and Deep Learning

---
