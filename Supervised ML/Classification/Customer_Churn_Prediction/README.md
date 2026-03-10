# 📊 Customer Churn Prediction (Business + ML)

## 🔹 Project Overview

Customer churn is a critical problem for telecom companies. Identifying customers likely to leave allows businesses to take proactive measures and reduce revenue loss.  
This project demonstrates an **end-to-end machine learning pipeline** for predicting churn, including:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and evaluation
- Feature importance analysis
- Model comparison
- Business insights and future improvements

---

## 📂 Dataset

The dataset contains **7043 customer records** with 21 features:

- `customerID` – Unique customer identifier  
- `gender` – Male or Female  
- `SeniorCitizen` – Whether the customer is a senior citizen (0,1)  
- `Partner` – Whether the customer has a partner  
- `Dependents` – Whether the customer has dependents  
- `tenure` – Number of months the customer has stayed  
- `PhoneService` – Whether the customer has phone service  
- `MultipleLines` – Whether the customer has multiple lines  
- `InternetService` – Type of internet service (DSL, Fiber optic, None)  
- `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies` – Yes/No for various services  
- `Contract` – Contract type (Month-to-month, One year, Two year)  
- `PaperlessBilling` – Whether paperless billing is enabled  
- `PaymentMethod` – Payment method used  
- `MonthlyCharges` – Monthly subscription charges  
- `TotalCharges` – Total charges for the customer  
- `Churn` – Target variable (Yes/No)

**Dataset shape:** 7043 rows × 21 columns  
**Churn distribution:**  
- No: 5174  
- Yes: 1869

---

## 🔹 Exploratory Data Analysis (EDA)

- Checked for **missing values**; only `TotalCharges` had 11 missing entries  
- Analyzed **categorical features**:  
  - Month-to-month contract customers have higher churn  
  - Gender distribution is nearly equal  
- Analyzed **numerical features**:  
  - Customers with higher `MonthlyCharges` are more likely to churn  
  - Longer `tenure` decreases churn probability  
- Visualizations:
  - Countplots for churn vs categorical features  
  - Boxplots for churn vs numerical features  

---

## 🔹 Data Preprocessing

- Converted `TotalCharges` to numeric  
- Handled missing values  
- Encoded categorical features using **One-Hot Encoding**  
- Split dataset into **training and test sets** (80:20)  

---

## 🤖 Machine Learning Models

We trained and evaluated **multiple classification models**:

### 1️⃣ Logistic Regression

- Accuracy: **78.7%**  
- AUC Score: **0.832**  


### 3️⃣ Random Forest Classifier

- Accuracy: **78.5%**  
- AUC Score: **0.815**  

  
### 4️⃣ XGBoost Classifier

- Accuracy: **77.4%**  
- AUC Score: **0.811**  

  
---

## 📈 Model Comparison

AUC scores of all models:

| Model                  | AUC Score |
|------------------------|-----------|
| Logistic Regression    | 0.832     |
| Random Forest          | 0.815     |
| XGBoost                | 0.811     |
| Decision Tree          | 0.664     |

---

## 📊 Feature Importance (Random Forest)

Top 10 features influencing churn prediction:

| Feature Index | Importance |
|---------------|------------|
| 3             | 0.193      |
| 2             | 0.170      |
| 1             | 0.168      |
| 10            | 0.040      |
| 28            | 0.035      |
| 13            | 0.029      |
| 25            | 0.029      |
| 4             | 0.027      |
| 19            | 0.026      |
| 26            | 0.025      |

---

## 💼 Business Insights

- Customers with **high monthly charges** are more likely to churn.  
- **Month-to-month contract** increases churn risk.  
- **Tenure, internet service type, and payment method** significantly influence churn.  
- Actionable insights for the business:
  - Offer **personalized retention plans**  
  - Provide **special deals for at-risk customers**  
  - Reduce churn and **increase revenue**

---

## 📝 Conclusion

This project demonstrates an **end-to-end machine learning workflow** for a real business problem: customer churn prediction.  
The **Logistic Regression model** achieved the best performance on this dataset.  
Feature importance analysis and insights provide guidance for **strategic business decisions**.

---

## 👩‍💻 Author

**Diya Patel**
– Data Science Enthusiast & Aspiring Machine Learning Engineer  

This project demonstrates end-to-end ML workflow and actionable business insights for customer churn prediction.  

