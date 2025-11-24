# 🚢 Titanic Survival Prediction – Machine Learning Project  
### Internship Task – Task 5 (Machine Learning)

This repository contains a complete Machine Learning workflow built on the **Titanic Survival Dataset**.  
The project covers data cleaning, exploratory data analysis, feature engineering, model training, model comparison, and final predictions.

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| **Task05_EDA_Titanic.ipynb** | Main notebook containing full ML pipeline |
| **SVMtrain.csv** | Dataset used for model training/testing |
| **README.md** | Project documentation |

---

## 🔍 Project Workflow

### **1. Data Loading**
- Loaded the Titanic training dataset using pandas.
- Displayed first few rows and dataset structure.

### **2. Basic Information & Missing Values**
- Identified datatypes, null values, and overall dataset summary.
- Checked missing values in *Age* and *Fare*.

### **3. Data Cleaning**
- Handled missing values using median replacement.  
- Converted categorical columns to numeric using `get_dummies()`.

### **4. Train–Test Split**
- Separated features (X) and target variable (Survived).
- Split into **80% training** and **20% testing**.

### **5. Feature Scaling**
- Applied `StandardScaler()` for normalization.

---

## 🤖 Models Trained

Four machine learning models were trained:

| Model | Status |
|-------|--------|
| Logistic Regression | ✔ Trained |
| Support Vector Machine (SVM) | ✔ Trained |
| Random Forest Classifier | ✔ Trained |
| K-Nearest Neighbors (KNN) | ✔ Trained |

All models were evaluated using:

- Accuracy Score  
- Classification Report  
- Confusion Matrix  

---

## 📊 Model Accuracies

| Model | Accuracy |
|-------|----------|
| **SVM** | **0.8146** |
| Logistic Regression | 0.7921 |
| Random Forest | 0.7977 |
| KNN | 0.7977 |

🔹 **Best Model Selected: SVM**

---

## 📉 Model Comparison Chart

A bar chart comparison was created using seaborn to visualize performance differences between models.

---

## 🏆 Final Model Prediction

- Final model used: **SVM**
- Predictions generated on the test set.
- Displayed the complete classification report for final evaluation.

---

## 📌 Technologies Used

- Python  
- Pandas  
- NumPy  
- Seaborn & Matplotlib  
- Scikit-learn (Machine Learning)

---

## 📬 Contact

If you have any questions or need help with improvements, feel free to reach out!

---

🎉 *This project was completed as part of my Machine Learning Internship – Task 5.*
