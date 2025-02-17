# Diabetes Prediction using Machine Learning

This repository contains a **Django-based web application** for predicting diabetes using machine learning models. The project compares multiple ML techniques to identify the most suitable model for diabetes prediction based on clinical parameters.

## 📌 Project Overview

Diabetes is a chronic condition affecting millions worldwide. Early detection can significantly improve disease management and reduce health risks. This study implements and compares various **machine learning models** to predict diabetes based on patient health parameters.

The **web application** allows users to enter relevant health data, and the trained ML model provides a prediction based on input parameters. The backend is built using **Django**, and the frontend is designed using **HTML & CSS**.

---

## 📊 Models Used

The following machine learning models were implemented and evaluated for performance:

- **Logistic Regression (LR)**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree (DT)**
- **Random Forest (RF)**
- **XGBoost (XgB)**

These models were trained and tested using the **scikit-learn** library to determine the most effective method for diabetes prediction.

---

## 🛠 Technologies Used

- **Programming Language:** Python  
- **Web Framework:** Django  
- **Frontend:** HTML, CSS  
- **Machine Learning Libraries:** scikit-learn, pandas, NumPy  
- **Developer Tools:** Jupyter Notebook, Google Colab  

---

## 📁 Dataset Description

The dataset contains **5,863** labeled chest X-ray images categorized as **Pneumonia/Normal**, stored in separate folders (`train`, `test`, `val`). However, for this diabetes prediction project, the dataset consists of patient records with **9 key features** influencing diabetes risk:

- **Gender**  
- **Age**  
- **Hypertension**  
- **Heart Disease**  
- **Smoking History**  
- **BMI (Body Mass Index)**  
- **HbA1c Level**  
- **Blood Glucose Level**  
- **Diabetes (Target Variable: 0 = No, 1 = Yes)**  

The dataset was preprocessed using **label encoding** to improve model accuracy.

---

## 📈 Results & Performance Analysis

The following table summarizes the accuracy achieved by different models:

| Model             | Accuracy   |
|-------------------|------------|
| Logistic Regression | **95.85%** |
| KNN               | **96.06%** |
| SVM               | **95.87%** |
| Decision Tree     | **95.26%** |
| Random Forest     | **96.99%** |
| XGBoost           | **97.12%** |

**🔹 XGBoost achieved the highest accuracy of 97.12%, making it the most effective model for diabetes prediction.**

---

## 🖥 How It Works

1️⃣ **User Inputs Health Parameters** (e.g., Age, Glucose Level, BMI, etc.)  
2️⃣ **Django Backend Processes Input & Runs ML Model**  
3️⃣ **The Trained Model Predicts Diabetes Risk**  
4️⃣ **Result is Displayed on the Web Application**  

---

## 📜 Conclusion

This study demonstrates the potential of machine learning, particularly **XGBoost**, in **accurate diabetes prediction**. The findings suggest that ML-based prediction tools can be integrated into **healthcare systems** for early diagnosis and patient monitoring.

**Further Research:** Future work may explore **deep learning** models and integrate additional health risk factors for enhanced accuracy.
