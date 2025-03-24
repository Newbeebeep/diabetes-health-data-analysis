# diabetes-health-data-analysis
xploratory data analysis on diabetes health indicators using Python

# 🩺 Diabetes Health Indicators – Data Analysis Project

This project explores the [Diabetes Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset) from the Behavioral Risk Factor Surveillance System (BRFSS) 2015 survey. The goal is to analyze health-related features and identify patterns associated with diabetes occurrence.

## 📊 Objective

To perform Exploratory Data Analysis (EDA) and extract key health indicators correlated with diabetes, using Python and data visualization libraries.

## 🧰 Tools & Technologies

- Python (Pandas, NumPy)
- Seaborn & Matplotlib (Data Visualization)
- Jupyter Notebook
- Git & GitHub

## 📂 Dataset Overview

- **Original rows**: ~253,000  
- **Target variable**: `Diabetes_012`  
    - `0` = No diabetes  
    - `1` = Diagnosed diabetes  
    - `2` = Borderline or unclear (excluded from analysis)  
- Cleaned dataset: only rows with values `0` and `1` were retained

## 📌 Key Steps

### 1. Data Cleaning
- Removed rows with `Diabetes_012 = 2`
- Checked for missing values (none found)

### 2. Visualizations
- **Bar chart**: Distribution of diabetes vs. non-diabetes cases
- **Box plots**: BMI & Age distributions by diabetes status
- **Heatmap**: Correlation matrix across all features

### 3. Insights

- People with diabetes tend to have:
  - Higher **BMI**
  - Higher **age**
  - Greater likelihood of **high blood pressure**
  - More difficulty walking
- Most features showed **weak individual correlation**, but collectively they can help with modeling

## 📈 Next Steps (Future Work)

- Build a classification model (Logistic Regression or Random Forest)
- Explore SMOTE or other resampling methods to handle class imbalance
- Create an interactive dashboard in Power BI or Tableau

## 📎 Acknowledgments

- Dataset Source: [Kaggle – Diabetes Health Indicators](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)
- Part of my Data Analytics Portfolio @ Nashville Software School

---

