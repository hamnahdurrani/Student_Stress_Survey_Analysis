# Student Stress Survey Analysis  
---

## Table of Contents
1. [Overview](#Overview)
2. [Dataset](#Dataset)
3. [Key Steps](#Key-Steps)
4. [Key Insights](#Key-Insights)
4. [Tech Stack](#Tech-Stack)
5. [Potential Applications](#Potential-Applications)

--- 

## Overview  
This project analyzes survey responses from **843 college students (ages 18–21)** to explore emotional, academic, and lifestyle factors contributing to stress. Using **Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)**, the dataset was cleaned, processed, and analyzed to uncover correlations, stress indicators, and demographic trends.  

---

## Dataset  
- Source: [Kaggle – Student Stress Monitoring Dataset](https://www.kaggle.com/)  
- Size: 843 rows × 26 columns  
- Features:  
  - **Demographics:** Gender, Age  
  - **Emotional Indicators:** Anxiety, Sadness, Irritability, Loneliness  
  - **Health Indicators:** Sleep issues, Headaches, Palpitations, Illness  
  - **Academic & Social Factors:** Workload, Competition, Extracurricular conflicts, Home/Work environment  
  - **Stress Type:** Eustress, No Stress, Distress

---

## Key Steps  
1. **Data Cleaning & Preprocessing**  
   - Removed duplicates and irrelevant columns  
   - Renamed features for readability  
   - Encoded categorical variable *Stress Type* using one-hot encoding  

2. **Exploratory Data Analysis (EDA)**  
   - **Univariate Analysis:** Distribution of features, skewness, outliers  
   - **Bivariate Analysis:** Stress levels across gender and age groups  
   - **Correlation Analysis:** Identified top predictors of stress (palpitations, anxiety, extracurricular conflict)  
   - **Co-occurrence Analysis:** Examined overlap of symptoms and stressors  

3. **Visualization**  
   - Histograms, count plots, and bar plots to display distributions  
   - Heatmaps for correlation and symptom co-occurrence  
---

## Key Insights  
- **Sleep issues** were the most common stress symptom, followed by palpitations and anxiety.  
- **Men aged 19–20** reported the highest stress levels.  
- **Extracurricular conflicts** and **low academic confidence** were leading stressors.  
- Majority of students experienced **positive stress (eustress)**, which can enhance performance.

---

## Tech Stack  
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy  

---

## Potential Applications  
- Build **predictive models** to detect at-risk students early.  
- Support **mental health programs** in universities with data-driven insights.  
- Extend framework to **employee/organizational stress analysis**.
  
