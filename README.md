# 🧑‍💼 Employee Salary Prediction - Capstone Project

This capstone project aims to build a machine learning model that predicts whether an employee earns more than ₹50,000 annually based on various demographic and professional features from the Adult Census Income dataset. The best-performing model is deployed as a user-friendly web application using Streamlit.

## 🎯 Problem Statement

Predict employee income category (`>50K` or `≤50K`) using features such as:

- Age
- Education
- Occupation
- Hours worked per week
- Experience

Accurate prediction assists in understanding income distribution and making HR decisions. The project tackles challenges such as handling mixed data types, cleaning missing values, and model selection.

## 🛠️ System Development Approach

### 💻 Technologies Used
- **Programming Language:** Python 3.13.0
- **Environment:** Jupyter Notebook
- **Deployment:** Streamlit
- **Version Control:** Git & GitHub

### ⚙️ System Requirements
- **Processor:** Intel Core i5 or higher
- **RAM:** 8 GB (16 GB recommended)
- **Storage:** 256 GB SSD
- **OS:** Windows 10/11, macOS, or Linux

## 📦 Libraries & Tools

- `pandas` – Data manipulation
- `numpy` – Numerical operations
- `matplotlib.pyplot` – Visualization
- `scikit-learn` – ML models & evaluation
- `joblib` – Model saving
- `streamlit` – Web app deployment

### **Model Training**
Trained 5 models:
- Logistic Regression
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gradient Boosting

### **Model Evaluation**
| Model                | Accuracy   |
|---------------------|------------|
| Logistic Regression | 79.02%     |
| Random Forest       | 78.09%     |
| KNN                 | 77.15%     |
| SVM                 | 80.05%     |
| **Gradient Boosting**  | **80.87%** ✅ |

## 📌 Conclusion

- Successfully built and deployed a model to classify employee income with 80.87% accuracy.
- Gradient Boosting outperformed all other models.
- Developed Streamlit app provides user-friendly access to predictions.
