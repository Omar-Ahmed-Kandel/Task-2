# 🛳 Titanic Dataset — Exploratory Data Analysis (EDA)

## 📌 Introduction
This project performs an exploratory data analysis (EDA) on the **Titanic dataset**.  
It covers data loading, inspection, cleaning, and visualization — with a focus on survival rates and distributions (Age, Fare), including breakdowns by **gender** and **passenger class**.


## Table of Contents
1. [Executive Summary](#executive-summary)
2. [Objectives & Key Questions](#objectives--key-questions)
3. [Data Preparation](#data-preparation)
4. [Key Measures & KPIs](#key-measures--kpis)
5. [Insights & Recommendations](#insights--recommendations)
6. [Limitations](#limitations)
7. [Next Steps & Decisions](#next-steps--decisions)

---

## 📄 Executive Summary
This notebook follows a **classic EDA workflow**:
1. **Data ingestion**
2. **Exploration**
3. **Cleaning**
4. **Visualization**

Cleaning actions:
- Removed columns with heavy missing values
- Filled missing values in specific columns (`Age`, `Embarked`)
- Removed duplicate rows
- Converted data types where necessary

Visualizations include:
- Overall survival rate
- Survival rate by gender and passenger class
- Age and fare distributions
- Bonus: survival rate by class **and** gender

---

## 🎯 Objectives & Key Questions
The analysis is designed to answer:
- What is the **overall survival rate**?
- How does survival vary by **gender**?
- How does survival vary by **passenger class**?
- How are **age** and **fare** distributed, and how might they relate to survival?
- How do **class** and **gender** interact with survival?

---

## 🛠 Data Preparation
### Cleaning Steps
- **Remove**: columns with high missing values
- **Fill**: missing values for `Age` and `Embarked`
- **Drop**: duplicate rows
- **Convert**: data types as needed

---

## 📊 Key Measures & KPIs
- **Overall Survival Rate**
- **Survival Rate by Gender**
- **Survival Rate by Passenger Class**
- **Age & Fare Distributions**
- **Survival Rate by Class & Gender** 

---

## 💡 Insights & Recommendations
From the visualizations:
- Clear survival differences across **gender** and **class**
- Age and fare show notable spread that may relate to survival likelihood

---

## ⚠ Limitations
- **Exploratory only** — no predictive models or hypothesis tests
- Dropping columns with many missing values reduces dimensionality
- Imputation methods (for Age & Embarked) are not compared with alternatives

---

## 🚀 Next Steps
- Use cleaned dataset for **classification models** or **statistical tests**
- Perform **feature engineering** and evaluate alternative imputation methods
- Consider deeper interaction effects between features

---

## Dataset
<a href = "https://github.com/Omar-Ahmed-Kandel/Task-2/blob/main/train.csv">Dataset</a>
