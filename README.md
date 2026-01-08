# Salary Analysis – Exploratory Data Analysis & Insights

## 📌 Project Overview
This project focuses on an exploratory and business-oriented analysis of employee salary data.  
The primary objective is to understand how key factors such as **gender, job title, education level, and experience** influence salary distribution.



salary-analysis/
│
├── data/
│   └── Salary_Data.csv
│
├── src/
│   ├── __init__.py
│   ├── load_data.py
│   ├── analysis.py
│   └── visualization.py
│
├── notebooks/
│   └── exploratory_analysis.ipynb
│
├── requirements.txt
├── README.md
└── main.py


Rather than building a predictive model, the emphasis is on **data understanding, pattern discovery, and actionable insights**, similar to real-world analytics tasks in HR, compensation, and workforce planning.

---

## 📊 Dataset
The dataset contains employee-level salary information with the following key attributes:

- Gender  
- Job Title  
- Education Level  
- Years of Experience  
- Salary  

📁 Raw dataset location:

`data/Salary_Data.csv`


---

## 🔍 Analysis Approach
The analysis follows a structured exploratory data analysis (EDA) workflow:

1. **Data Cleaning**
   - Handling missing and inconsistent values
   - Standardizing categorical variables (e.g. Gender)

2. **Descriptive Statistics**
   - Overall salary distribution
   - Average salary comparisons across categories

3. **Group-Based Analysis**
   - Salary differences by gender
   - Salary distribution across job titles
   - Combined analysis of gender and job role

4. **Visualization**
   - Bar charts for average salary comparisons
   - Clear, business-friendly visual storytelling

---

## 📈 Key Insights
Some of the questions explored in this analysis include:

- Are there observable salary differences across genders?
- Which job titles command the highest average salaries?
- How does role-based segmentation impact compensation levels?
- Are minority categories (e.g. low-frequency gender groups) statistically meaningful?

These insights are intended to mirror the type of exploratory analysis performed in **HR analytics, compensation benchmarking, and organizational planning**.

---

## 🧪 Tools & Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

📁 Analysis notebook:

`notebooks/salary_analysis.ipynb`

---

## 🚀 How to Run
```bash

'pip install pandas matplotlib'
jupyter notebook notebooks/salary_analysis.ipynb




