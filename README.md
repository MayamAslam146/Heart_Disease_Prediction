# Heart_Disease_Prediction
This project analyzes heart disease data using EDA, data preprocessing, and ML models. The best model was saved as a pickle file for deployment. 🚀

# Heart Disease Data Analysis and Prediction 🩺📊

This repository contains a Jupyter Notebook analyzing heart disease data. The analysis includes statistical observations, missing value imputation, and distribution analysis.

## 📌 Project Overview

The dataset provides insights into heart disease cases based on different parameters such as age, gender, cholesterol levels, and fasting blood sugar. The analysis focuses on:

- Age and gender distribution of heart disease cases
- Regional variations in heart disease prevalence
- Chest pain analysis and categorization
- Handling missing values using machine learning (Random Forest Classifier)
- Normal distribution and skewness observations in various parameters

## 📊 Key Observations

### 1️⃣ Age Analysis  
- Minimum age: **27 years**, Maximum age: **77 years**  
- Most people develop heart disease between **52 to 54 years**  

### 2️⃣ Gender Distribution  
- **Males:** **78.91%**  
- **Females:** **21.09%**  
- Males are **274.23%** more than females in the dataset  

### 3️⃣ Regional Distribution  
- **Most cases:** **Cleveland (304 cases)**  
- **Least cases:** **Switzerland (123 cases)**  
- **Most females:** **Cleveland (97)**  
- **Least females:** **VA Long Beach (6)**  
- **Most males:** **Hungary (212)**  
- **Least males:** **Switzerland (113)**  

### 4️⃣ Mean, Median, and Mode Analysis  
- Mean, median, and mode differ across countries with respect to age  

### 5️⃣ Chest Pain Analysis  
- **426 males** and **70 females** suffer from **asymptomatic chest pain**  
- **144 cases** of asymptomatic chest pain reported in **Cleveland**  
- **36 males** and **10 females** suffer from **typical angina**  

### 6️⃣ Handling Missing Values  
- Missing values in **thal, slope, fbs, exang, and restecg** were imputed using a **Random Forest Classifier**  
- **30 missing values** in **chol**, but **chol == 0** is **not an outlier**  

---

## 📈 Observations on Normal Distribution & Skewness  

### ✅ Normally Distributed Data  

#### **Restops:**  
- **Males:** 127.5 - 138.4 (**165 cases**)  
- **Females:** 127.5 - 132.4 (**39 cases**)  

#### **Other Observations:**  
- **Females:** 197.5 - 202.4 (**6 cases**)  
- **Males:** 197.5 - 202.4 (**2 cases**)  
- **Coconuts (Males):** 77.5 - 82.4 (**Lowest values observed**)  
- No females observed in this range  

#### **Regional Data:**  
- **VA Long Beach:** Males: 127.5 - 132.4 (**77 cases**)  
- **Hungary:** Females: 117.5 - 122.4 (**21 cases**)  

---

### ⚠️ Skewed Data (Cholesterol - "Chol")  

#### **Chad (Highly Skewed)**  
- **Males:** 210 - 229 (**101 cases**)  
- **Females:** 190 - 209 (**31 cases**)  

#### **Cleveland:**  
- **Males (41 cases)** suffer from **high cholesterol**  

#### **Hungary:**  
- **Females (8 cases):** 190 - 207  
- **Others:** 230 - 249  

---

### 🚨 Highly Skewed Data (Fasting Blood Sugar - "fbs")  

#### **Hungary:**  
- **196 males** have **high fasting blood sugar**  

#### **VA Long Beach:**  
- **65 males** observed with **0 fbs**  

#### **Switzerland:**  
- **1 male** observed with **2 fbs**  
- **107 males** observed with **0 fbs**  

---

## 🔍 Additional Observations  

### **Restecg (Resting Electrocardiographic Measurement)**  
- **Normally Distributed**  
- Hungary: **Males (778), Females (58)**  

### **Thalch (Thalassemia)**  
- **Slightly Skewed**  
- **Long Beach:** Males (66), values **137.5 - 142.4**  
- **Uotewland:** Females (16), values **157.5 - 162.4**  

### **Exang (Exercise-Induced Angina) – Highly Skewed**  
- **Hungary:** **138 males** with **0 exang**  
- **Cleveland:** **75 females** with **0 exang**  
- **Long Beach:** **125 males** with **1 exang**  
- **Cleveland:** **22 females** with **1 exang**  

---

## 📝 How to Use This Repository  

1. Clone this repository:  
   ```bash
   git clone https://https://github.com/MayamAslam146/Heart_Disease_Prediction.git
