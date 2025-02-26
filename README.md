# 🏥 Breast Cancer Classifier  

A machine learning model to classify breast cancer as **Malignant (M)** or **Benign (B)** based on input features. The project explores different ML algorithms, hyperparameter tuning, and model evaluation techniques to achieve high accuracy.  

---

## 📌 Features  
✅ **Algorithms Used:**  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest  
- Gradient Boosting  

✅ **Techniques Applied:**  
- **GridSearchCV** for hyperparameter tuning  
- **StandardScaler** for feature scaling (SVM & Logistic Regression)  
- **ROC Curve** analysis  
- **Model evaluation using Accuracy, Precision, and Recall**  

---

## 📊 Model Performance  
| Model              | Accuracy | Precision | Recall |
|--------------------|----------|-----------|--------|
| **Logistic Regression** | **97%** | 0.98 | 0.95 |
| **SVM**            | 96%      | 0.98      | 0.93   |
| **Random Forest**  | 96%      | 1.00      | 0.88   |
| **Gradient Boosting** | 96%  | 1.00      | 0.88   |

---

## 📂 Dataset  
- The dataset used is the **Breast Cancer Wisconsin Dataset**, which contains various cell-based features to classify tumors.  
- **Preprocessing:** Missing values handled, feature scaling applied.  
- Dataset: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data
---
