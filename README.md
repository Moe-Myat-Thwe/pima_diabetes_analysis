# 🩺 Pima Diabetes Analysis — Data Analysis with Python

This project performs an end-to-end exploratory data analysis (EDA), and data preprocessing using the **Pima Indians Diabetes Dataset**.
The goal is to understand what factors influence diabetes occurrence.

---

## 📁 Project Structure


├── pima_diabetes_analysis.ipynb   # Main analysis notebook

├── diabetes.csv                   # Dataset folder

├── README.md                      # Project documentation

---

## 🎯 Project Objectives

* Perform **data cleaning**, **missing value handling** (This data is already clean and no missing values), and **feature engineering**.
* Conduct **EDA** to uncover relationships between health indicators and diabetes outcomes.
* Create clear **plots and insights** to support decision-making.

---

## 📊 Dataset Description

The dataset includes the following health-related attributes:

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age
* Outcome (Target: 1 = Diabetes, 0 = No Diabetes)

---

## 🔍 Key Steps in the Notebook

### 1. **Data Loading**

* Import CSV file into Pandas
* Inspect structure and summary statistics

### 2. **Data Cleaning**

* Detect Data Type
* Detect missing or zero-values
* Detect duplicates

### 3. **Feature Engineering**

* BMI_Category, AgeGroup, Pregnancy_Group


### 4. **Exploratory Data Analysis**

Includes:

* Distribution plots
* Correlation heatmap
* Boxplots and pairplots
* Outcome-based comparisons


## 📦 Requirements

Typical libraries:

* pandas
* numpy
* matplotlib
* seaborn
* jupyter

## 📁 Output

The notebook generates:

* Cleaned dataset 
* Visualizations (correlation heatmap, histograms, boxplots, etc.)
* Key insights about diabetes risk factors

---


