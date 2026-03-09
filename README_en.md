# 📊 Telecom X — Part 1  
## Customer Churn Analysis (ETL + EDA)

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualización-4C72B0?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

*Read this in other languages: [English](README_en.md), [Español](README.md).*

---

## 🔗 Full Project

This repository corresponds to **Part 1 (ETL + EDA)** of the Telecom X project.

📌 **Part 2 (Machine Learning — Predictive Modeling)** is available here:  
👉 https://github.com/ernes2111/Challenge-Telecom-X-part2

Both parts make up a complete **end-to-end** flow, where this stage prepares and analyzes the data that will later be used to build the predictive model in Part 2.

---

## 📌 Project Description

This project aims to analyze customer churn in the company **Telecom X**, identifying the factors that influence service cancellation.

Through a complete process of **ETL (Extract, Transform, Load)** and **Exploratory Data Analysis (EDA)**, relevant patterns are identified that serve as a basis for:

- Data-driven retention strategies.
- Construction of predictive models (developed in Part 2).

---

## 🎯 Objectives

- Understand the magnitude of churn in the company.
- Identify variables associated with cancellation.
- Analyze patterns in categorical and numerical variables.
- Generate strategic insights based on data.
- Prepare the dataset for subsequent predictive modeling.

---

## 🧱 Project Structure

The project is organized into the following stages within the `TelecomX_LATAM_en.ipynb` notebook:

### 1️⃣ Extraction
- Import data from a structured source (JSON).
- Normalization of nested columns using `pd.json_normalize()`.

### 2️⃣ Transformation
- Cleaning and variable typing.
- Conversion of binary variables.
- Creation of a new variable `Cuentas_Diarias` (Daily Accounts).
- Standardization of column names.
- Generation of the clean dataset `datos_tratados.csv` (input for Part 2).

### 3️⃣ Load and Analysis (EDA)
- Descriptive analysis (mean, median, standard deviation).
- General churn distribution.
- Churn analysis by categorical variables.
- Churn analysis by numerical variables.
- Correlation matrix and additional analysis.

### 4️⃣ Final Report
- Strategic conclusions.
- Recommendations to reduce churn.
- Identification of key variables for future modeling.

---

## 📊 Key Findings

- The churn rate is approximately 27%.
- Month-to-month contracts have the highest cancellation rate.
- Customer tenure is the most influential factor (negative relationship with churn).
- Customers with higher monthly charges have a higher tendency to cancel.
- Contractual stability significantly reduces the risk of churn.

These findings were subsequently validated quantitatively in **Part 2 using Machine Learning models**.

---

## 🛠️ Technologies Used

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## ▶️ How to Run the Project

Clone the repository:

```bash
git clone https://github.com/ernes2111/Challenge-Telecom-X.git
cd Challenge-Telecom-X
```
