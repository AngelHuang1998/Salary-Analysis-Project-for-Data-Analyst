# 📊 Data Science Salary Analysis Project

This project analyzes a global dataset of data science-related salaries to uncover insights about experience level, remote work, company size, and geographical differences. It includes data cleaning, exploratory analysis, and answers to several research questions using Python and Jupyter Notebook.

---

## 📌 Dataset Source & Adaptation

- **Original dataset from Kaggle:**  
  [Data Science Salaries 2023 by arnabchaki](https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023)
  (I have adapted the original material to suit the assignment requirements.)

---

## 🔍 Dataset Overview

- **Total records (after cleaning):** 2,357
- **Columns included:**
  - `experience_level`: EN / MI / SE / EX
  - `job_title`: 93 unique data science titles
  - `salary_in_usd`: Salary (USD, integer)
  - `remote_ratio`: 0 (On-site), 50 (Hybrid), 100 (Remote)
  - `company_location`: 72 countries
  - `company_size`: S / M / L

---

## 🧹 Data Cleaning Summary

- Removed 1,406 duplicate rows
- Handled missing values:
  - Dropped rows with missing `job_title`
  - Filled `company_size` with its mode
- Outliers in `salary_in_usd` (above 315,350) replaced with mean
- Converted data types for consistency

---

## ❓ Research Questions

1. 💼 **Does remote work ratio affect salary levels?**  
2. 🧠 **How do experience levels compare in terms of salary?**  
3. 🌍 **Which countries offer the highest salaries for data scientists?**  
4. 🏢 **How do company sizes impact salary ranges?**

> Full analysis and visualizations can be found in the [Project_Assignment.ipynb](Project_Assignment.ipynb).

---

## 🛠 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
