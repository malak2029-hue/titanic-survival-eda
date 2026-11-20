# Titanic Survival — Exploratory Data Analysis (EDA)

## 📌 Project Overview
An exploratory data analysis project using **Python** to examine passenger demographics, ticket classes, family size, and fare patterns in relation to survival rates on the Titanic.

## 🛠️ Tools & Libraries
- **Python**
- **Pandas** (data cleaning, feature engineering such as `FamilySize`, aggregation)
- **Matplotlib** (data visualization)
- **Jupyter Notebook / VS Code**

## 🧹 Data Cleaning & Preparation
- Inspected dataset structure, data types, and missing values.
- Handled missing values (e.g., `Age` imputation and missing-value treatment).
- Created `FamilySize` from `SibSp` and `Parch` to analyze group/family impact.

## 🔍 Key Insights
- **Gender & Passenger Class:** Survival rates differ noticeably across gender and ticket class (`Pclass`).
- **Age & Family Size:** Analyzing age distributions and `FamilySize` highlights how traveling alone vs. with family relates to survival.
- **Fare & Correlations:** Higher fare values and specific numerical features show clear relationships with survival outcomes.

## 📂 Repository Contents
- `titanic_eda.ipynb` — Full analysis notebook with code, outputs, and charts.
- `titanic.csv` — Dataset used for the analysis.

