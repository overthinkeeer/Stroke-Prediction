# 🧠 Stroke Prediction Project

This project aims to predict the probability of a person having a **stroke** based on medical and demographic data.  
The dataset comes from [Kaggle - Stroke Prediction Dataset](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset).

---

## 📌 Project Overview
Stroke is one of the leading causes of death and disability worldwide.  
The main goal of this project is to build and evaluate machine learning models that can predict stroke risk and help in early diagnosis.

---

## 📂 Project Structure
- **Exploratory Data Analysis (EDA):**
  - Distribution of features
  - Class imbalance analysis
  - Correlation between variables
- **Data Preprocessing:**
  - Handling missing values
  - Encoding categorical variables
  - Feature scaling
  - Balancing the dataset using SMOTENC
- **Modeling:**
  - Logistic Regression
  - Random Forest
  - K-Nearest Neighbors
  - Support Vecotr Machines
- **Evaluation:**
  - Accuracy, Precision, Recall, Custom F2-score
  - ROC-AUC curves
  - Threshold tuning

---

## ⚙️ Tech Stack
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Imbalanced-learn**
- **SHAP**
---

## 🚀 Key Results
- Class imbalance strongly affects performance.
- Lowering decision threshold improves **recall** (important for stroke detection).
- Final model achieves:
  - **Accuracy:** ~70%
  - **Recall:** ~75% (for stroke cases)
  - **AUC:** ~81.33%

---

## 📈 Future Improvements
- Feature engineering with domain-specific knowledge.
- Hyperparameter optimization.
- Testing on external datasets for generalization.
- Deployment as an API or web application.

---

## 📜 License
This project is for **educational purposes** only and should not be used for medical decisions.
