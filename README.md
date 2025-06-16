# 🎓 Predicting Student Depression Using Machine Learning

This project applies machine learning to predict depression among university students using a dataset of 27,901 entries containing demographic, academic, and lifestyle-related variables.
## 👥 Authors
Amit Dvash

Yuval Livshits

Guy Korenfeld

Tom Badash

Einav Cohen


## 🔍 Research Question

**What personal, academic, and lifestyle-related factors best predict depression among university students, and how accurately can machine learning models identify students at risk based on these features?**

---


## 📊 Dataset Overview

- **Source:** Survey-based data of 27,901 university students.
- **Features:**
  - Demographics: Age, Gender, City
  - Academics: CGPA, Degree, Academic Pressure, Study Satisfaction
  - Lifestyle: Sleep Duration, Dietary Habits, Financial Stress
  - Mental Health: Suicidal Thoughts, Family History of Mental Illness

---

## 🧠 Models & Methodology

The following models were implemented:

- `Random Forest` 
- `XGBoost` 
- `Neural Network` 
- `Ensemble Model` (Soft Voting)

All models were evaluated using:
- Accuracy
- F1-Score
- ROC-AUC
- Precision-Recall AUC
- Confusion Matrices
- Permutation Feature Importance

---

## 🏆 Key Findings

- **Best Model:** Neural Network (ROC-AUC = 0.93, F1 = 0.85)
- **Top Predictors:**
  - Suicidal Thoughts
  - Academic Pressure
  - Lifestyle Score (engineered feature)
  - Financial Stress
- **Ensemble model** yielded stable, high-quality performance across all metrics.

---

## 🛠️ Technical Stack

- **Language:** Python 3.9.13
- **Environment:** Visual Studio Code
- **Frameworks:** Scikit-learn, XGBoost, Keras, NumPy, Pandas, Matplotlib
- **Version Control:** Git

---

## ⚙️ Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/guyko29/student-depression-model
    
2. Run the Student Depression Prediction.ipynb with python 3.9.13 version

