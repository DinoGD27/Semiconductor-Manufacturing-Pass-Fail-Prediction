# 🏭 Semiconductor Manufacturing Pass/Fail Prediction

## 📌 Project Overview

This project develops a Machine Learning classification model to predict whether a semiconductor manufacturing process results in a **Pass** or **Fail** outcome using sensor measurements.

The complete workflow includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Handling Missing Values
- Class Balancing using SMOTE
- Feature Standardization
- Machine Learning Model Training
- Hyperparameter Tuning
- Model Evaluation
- Model Saving

---

## 🎯 Business Problem

Modern semiconductor manufacturing processes generate hundreds of sensor readings for every manufactured unit.

The objective of this project is to identify whether a product will Pass or Fail quality inspection using sensor measurements collected during manufacturing.

Early prediction helps reduce manufacturing costs and improve production quality.

---

## 📊 Dataset Information

- Domain : Semiconductor Manufacturing
- Total Records : 1567
- Total Features : 591 Sensor Features
- Target Variable : Pass/Fail

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Imbalanced-Learn (SMOTE)
- Joblib
- Google Colab

---

## 🤖 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Missing Value Treatment
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. Train-Test Split
7. Feature Standardization
8. SMOTE (Class Balancing)
9. Model Training
   - Random Forest
   - Support Vector Machine (SVM)
   - Gaussian Naive Bayes
10. Hyperparameter Tuning (GridSearchCV)
11. Model Evaluation
12. Model Saving

---

## 📈 Machine Learning Models

| Model | Purpose |
|--------|---------|
| Random Forest | Ensemble Classification |
| Support Vector Machine | High-dimensional Classification |
| Gaussian Naive Bayes | Probabilistic Classification |

---

## 📊 Evaluation Metrics

The following metrics were used to evaluate model performance:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Cross Validation Score

---

## 📂 Project Structure

```text
Semiconductor-Manufacturing-Pass-Fail-Prediction/
│
├── Semiconductor_Manufacturing_Pass_Fail_Prediction.ipynb
├── sensor-data.csv
├── best_model.pkl
├── README.md
├── LICENSE
└── requirements.txt
```

---

## 🚀 Future Improvements

- Perform Feature Selection using PCA.
- Experiment with XGBoost and LightGBM.
- Build a Streamlit web application.
- Deploy the model on a cloud platform.

---

## 👨‍💻 Author

**Gnana Dino**

Aspiring Data Scientist | Python | Machine Learning | Data Analysis

---

⭐ If you found this project useful, consider giving it a star!
