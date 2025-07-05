# 🩺 Diabetes Prediction Web App

This is a **Flask-based Machine Learning web application** that predicts whether a person is diabetic or non-diabetic based on their medical attributes. The prediction is made using a trained ML model on the **Pima Indians Diabetes dataset**.

---

## 📌 Problem Statement

Diabetes is a chronic condition that affects millions of people worldwide. Early diagnosis is crucial for treatment and prevention. This application enables users to enter basic health-related parameters and predicts the likelihood of diabetes.

---

## 📊 Dataset Details

- **Dataset Name**: Pima Indians Diabetes Dataset  
- **Total Records**: 769  
- **Target**:  
  - `0` = Non-Diabetic  
  - `1` = Diabetic  

**Features Used**:
1. Pregnancies  
2. Glucose  
3. Blood Pressure  
4. Skin Thickness  
5. Insulin  
6. BMI  
7. Diabetes Pedigree Function  
8. Age

---

## ✅ ML Models Used

Multiple ML models were trained and evaluated:
- Logistic Regression  
- Decision Tree Classifier  
- Support Vector Classifier (SVC)  
- Bernoulli Naive Bayes  

The best-performing model was saved and used in the web app.

---

## 🛠 Tech Stack

| Tool / Library       | Purpose                  |
|----------------------|---------------------------|
| Python               | Programming Language      |
| Pandas, NumPy        | Data Analysis             |
| scikit-learn         | ML Model Building         |
| Flask                | Web Framework             |
| Pickle               | Model Serialization       |
| HTML/CSS             | Frontend Templates        |

---

## 🚀 Features

- Clean and responsive UI built with HTML and Flask
- Takes user inputs through a web form
- Predicts if a person is diabetic or not in real-time
- Displays result as **"Diabetic"** or **"Non-Diabetic"**

---

## 📂 Project Structure

