# 🚀 Customer Churn Rate Prediction

## 📌 Project Overview
Customer churn is a major challenge for subscription-based businesses.  
This project builds a **Machine Learning classification model** to predict whether a customer will churn based on demographic and service-related features.

The goal is to help businesses identify high-risk customers and improve customer retention strategies.

---

## 🎯 Business Objective
- Identify customers likely to churn.
- Reduce revenue loss.
- Provide actionable insights to improve retention.
- Support data-driven decision-making.

---

## 📂 Dataset Description
The dataset includes customer information such as:

- Gender  
- Tenure  
- Internet Service  
- Contract Type  
- Monthly Charges  
- Total Charges  
- Churn (Target Variable)

### 🎯 Target Variable
**Churn**  
- Yes → Customer left  
- No → Customer stayed  

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  

---

## 🔎 Project Workflow

### 1️⃣ Data Cleaning
- Checked missing values
- Converted data types
- Handled inconsistent values
- Encoded categorical variables

---

### 2️⃣ Exploratory Data Analysis (EDA)

Performed visual analysis to understand:

- Churn distribution
- Impact of contract type on churn
- Tenure vs churn relationship
- Monthly charges vs churn
- Correlation between numerical variables

### 📊 Key Insights
- Customers with **month-to-month contracts** churn more.
- Higher monthly charges increase churn probability.
- Customers with longer tenure are less likely to churn.

---

### 3️⃣ Feature Engineering
- Label Encoding
- Feature Scaling
- Train-Test Split

---

### 4️⃣ Model Building

Implemented the following models:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier
- SVM
- KNN  

---

## 📊 Model Evaluation

Evaluation Metrics Used:

- Accuracy Score  
- Confusion Matrix  
- Precision  
- Recall  
- F1-Score  

### 🏆 Best Performing Model
Random Forest performed better compared to other models.

### 🔮 Improvements

- Hyperparameter tuning (GridSearchCV)

- Handle class imbalance

- ROC-AUC curve analysis

- Feature importance visualization

- Model deployment using Streamlit

### 🧠 Key Learnings

- End-to-end Machine Learning pipeline

- Importance of data preprocessing

- Model comparison techniques

- Business interpretation of ML results

- Practical implementation of classification algorithms

### 👨‍💻 Author

**Rohit Gharal**
Aspiring Data Scientist | Machine Learning Enthusiast
