# 🚢 AIML-Internship-Week2-UsmanAsif

**AI/ML Internship Program — Week 2 of 8**  
**Topic:** Data Analysis with NumPy & Pandas  
**Instructor:** Zain Ul Abideen | Digitech Offerings  

---

## 📌 Overview

This repository contains the complete Week 2 submission for the Digitech Offerings AI/ML Internship Program. The task involved performing a comprehensive Exploratory Data Analysis (EDA) on the Titanic passenger dataset using NumPy and Pandas. The project covers data cleaning, feature engineering, statistical analysis, and the creation of a professional visualization dashboard.

---

## 📊 Dataset

| Property | Detail |
|---|---|
| Name | Titanic — Machine Learning from Disaster |
| Source | Kaggle / Seaborn Built-in Dataset |
| Rows | 891 passengers |
| Columns | 12 original features |
| Target | `Survived` (0 = No, 1 = Yes) |

---

## 🔍 Top 3 Survival Insights

**1. Gender is the strongest predictor of survival.**  
Female passengers had a survival rate of approximately **74.2%**, compared to only **18.9%** for males.

**2. Passenger class created a clear survival hierarchy.**  
First-class passengers had a survival rate of around **63.0%**, while third-class passengers had only **24.2%**.

**3. Traveling alone reduced survival chances.**  
Passengers traveling alone had a survival rate of approximately **30.4%**, compared to **50.6%** for those traveling with family.

---

## 📂 Repository Structure

```
AIML-Internship-Week2-UsmanAsif/
│
├── Week2_Titanic_Analysis.ipynb
├── titanic_cleaned.csv
├── titanic_dashboard.png
└── README.md
```

---

## 📸 Dashboard Preview

<img width="2400" height="2700" alt="titanic_dashboard" src="https://github.com/user-attachments/assets/bb9a4b7c-5524-4b7b-bc71-fed071cbc0ac" />


---

## ⚙️ Project Coverage

### 🔹 Part A — NumPy & Data Loading
- NumPy broadcasting, masking, and vectorized operations  
- Dataset inspection (shape, data types, missing values)

### 🔹 Part B — Data Cleaning & Feature Engineering
- Missing value handling (Age, Embarked, Cabin)  
- Outlier detection using IQR and capping  
- Feature engineering:
  - `family_size`, `is_alone`, `fare_per_person`
  - `age_group`, `fare_bin`
- Encoding (binary, one-hot, ordinal)  
- Feature scaling using StandardScaler  

### 🔹 Part C — Statistical Analysis
- Survival analysis using GroupBy  
- Aggregations and custom functions  
- Pivot tables and heatmaps  
- Correlation matrix analysis  

### 🔹 Part D — Dashboard & Report
- NumPy statistical calculations  
- Z-score normalization  
- 6-chart EDA dashboard  
- Final structured report  

---

## 🛠️ Tools & Libraries

- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Missingno  
- Scikit-learn  

---

## ▶️ How to Run

1. Open `Week2_Titanic_Analysis.ipynb` in Google Colab  
2. Run all cells (`Runtime → Run all`)  
3. Dataset loads automatically via seaborn  
4. Output files will be generated  

---

## 📌 Submission Details

- **Student:** Usman Asif  
- **Program:** AI/ML Internship  
- **Week:** 2 of 8  
- **Instructor:** Zain Ul Abideen  
- **Deadline:** 3rd May 2026  

---

## 🏁 Conclusion

This project demonstrates a complete data analysis workflow, including preprocessing, feature engineering, and visualization. The results highlight how gender, passenger class, and fare significantly influenced survival outcomes.

---
