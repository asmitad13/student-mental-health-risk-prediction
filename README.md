# student-mental-health-risk-prediction


# 🧠 Student Mental Health Risk Prediction

A real-world data science project that uses academic, behavioral, and lifestyle indicators to predict student mental health risk levels (Low, Medium, High). Built with Random Forest, SMOTE, SHAP, and Tableau for explainability and visualization.

---

## 📂 Dataset

- **Source:** UCI Student Performance Dataset  
- **Records:** 395 students  
- **Features:** 33 variables (grades, absences, alcohol use, parental education, etc.)

---

## 🧠 Objective

Identify students at **risk of mental health decline** using behavioral and academic indicators.  
This project simulates a real-world school scenario where early intervention could be triggered based on predicted risk levels.

---

## 📊 Target Variable

A **custom `mental_health_risk` score** was engineered based on:
- Final grades (G1, G2, G3)
- Absences
- Study time
- Sleep and screen time (where applicable)
- Alcohol consumption (`Dalc`, `Walc`)

---

## 🛠️ Tech Stack

- **Python** (Pandas, scikit-learn, imblearn)
- **Random Forest Classifier**
- **SMOTE** for class imbalance handling
- **SHAP** for model explainability
- **Tableau** for final dashboard visualization

---

## 📈 Model Performance

| Model                   | Accuracy | High Risk Recall | Medium Risk Recall |
|------------------------|----------|------------------|--------------------|
| Logistic Regression     | 79.7%    | 17%              | 33%                |
| Random Forest           | 74.6%    | 0%               | 27%                |
| ✅ Random Forest + SMOTE| **78.4%**| **33%**          | **27%**            |

---

## 📊 Tableau Dashboard

Link: 

---

## 🔍 SHAP Insights

SHAP visualizations showed:
- **Absences**, **study time**, and **alcohol use** were key predictors of mental health decline.
- Risk is **negatively correlated with academic performance** and **positively correlated with behavioral warning signs**.

---

