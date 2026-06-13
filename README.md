# 🐍 Python Fundamentals — Capstone Project

A hands-on data wrangling project using Python (Pandas & NumPy) to 
manipulate, clean, and analyze employee and project datasets.

---

## 📁 Dataset Overview

Three interconnected datasets:
- **Employee** — ID, Name, Gender, City, Age
- **Project** — ID, Project, Cost, Status
- **Seniority Level** — ID, Designation Level

---

## 🔧 Tasks Completed

| Task | Description |
|------|-------------|
| 1 | Created 3 dataframes and exported as CSV files |
| 2 | Handled missing cost values using running average (For loop) |
| 3 | Split full name into First Name & Last Name columns |
| 4 | Merged all 3 dataframes into a single `Final` dataframe |
| 5 | Added 5% bonus column for employees with finished projects |
| 6 | Demoted designation on failed projects; removed ineligible employees |
| 7 | Added Mr./Mrs. prefix based on gender; dropped gender column |
| 8 | Promoted designation for employees aged 29+ (IF condition) |
| 9 | Aggregated total project cost per employee into `TotalProjCost` |
| 10 | Filtered employees by city names containing the letter "o" |

---

## 🛠️ Tools & Libraries

🐍 Python · 🐼 Pandas · 🔢 NumPy · 📓 Jupyter Notebook

---

## 📂 Files

- `PythonCapstone.ipynb` — Full code with comments and outputs
- `employee.csv` — Employee dataset
- `project.csv` — Project dataset
- `seniority.csv` — Seniority level dataset

---

## 💡 Key Concepts Applied

- Data cleaning & missing value treatment
- DataFrame merging & joining
- Conditional logic & loops
- Feature engineering (bonus, prefix, designation updates)
- String manipulation & filtering
