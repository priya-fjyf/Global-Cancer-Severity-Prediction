# 🌍 Global Cancer Patients Severity Prediction
Machine Learning project to predict cancer severity scores in global patients using medical, lifestyle, and environmental features. Models used: Linear Regression, Random Forest

This project predicts the **severity of cancer** in global patients based on medical, lifestyle, and environmental factors. The output is a numerical **Target Severity Score**, representing how serious the condition is.

---

## 📁 Dataset Summary

- Records: 5000
- Key Features:
  - Age, Gender, Country
  - Genetic Risk, Smoking, Alcohol Use, Obesity, Pollution
  - Cancer Type, Stage, Treatment Cost, Survival Years
- Target: `Target_Severity_Score` (continuous)

> `Patient_ID` dropped as it holds no predictive value.

---

## ⚙️ Tools Used

- Python, Pandas, NumPy
- Scikit-learn, Seaborn, Matplotlib
- Category Encoders

---

## 🧠 Models Used

- Linear Regression
- Random Forest


Performance evaluated using **R² Score** and **RMSE**.

---

## 📊 Key Findings

- Cancer type & stage affect severity significantly.
- Lifestyle factors (obesity, smoking) have strong correlation.
- Target Encoding improved model accuracy.

---

## 🚀 Future Scope

- Add SHAP/LIME for model explainability.
- Build dashboard for doctors using Streamlit.

---

## ⭐ If you find this helpful, please give it a star!


