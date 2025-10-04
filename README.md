# 🧠 Data Engineer Salary Analysis (2024)

## 📘 Overview

This project explores the **2024 Data Engineer Salary dataset** to identify key factors influencing salary trends across experience levels, employment types, and company sizes.  
This project demonstrates practical data-mining skills, end-to-end analysis, and visual storytelling using Python.

The primary goal was to extract insights into the evolving data engineering job market and visualize salary patterns across multiple dimensions.

---

## 🎯 Objectives

- Perform **data cleaning, transformation, and exploratory data analysis (EDA)**.  
- Analyze **salary growth trends (2020–2024)**.  
- Examine how **experience level, job title, and company size** affect salaries.  
- Apply **encoding** to categorical variables for advanced analysis.  
- Visualize insights using **Matplotlib** and **Seaborn**.  

---

## ⚙️ Tools and Technologies

| Category | Tools / Libraries |
|-----------|------------------|
| Programming Language | **Python 3** |
| IDE | **Jupyter Notebook** |
| Data Analysis | **Pandas**, **NumPy** |
| Visualization | **Matplotlib**, **Seaborn** |
| Machine Learning / Preprocessing | **Scikit-learn (Encoding, Filtering)** |
| Dataset Source | **Kaggle – Data Engineer Salary Dataset (2024)** |

---

## 📊 Dataset Description

The dataset includes salary and employment data for various roles within the data domain.

| Column | Description |
|--------|--------------|
| `work_year` | Year of observation |
| `experience_level` | Junior (EN), Mid (MI), Senior (SE), Executive (EX) |
| `employment_type` | Full-time, Part-time, Contract |
| `job_title` | Job title (e.g., Data Engineer, AI Engineer, ML Engineer) |
| `salary`, `salary_in_usd` | Annual salary in original currency and USD |
| `employee_residence` | Country of residence |
| `company_location` | Company’s primary location |
| `company_size` | Small, Medium, Large organization size |

---

## 🚀 Running the Analysis

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Fatimashamilova/data-engineer-salary-analysis.git
cd data-engineer-salary-analysis
````

### 2️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook

Open Jupyter and execute:

```bash
jupyter notebook Project_Assignment_Scripts.ipynb
```

---

## 🔍 Key Steps in the Notebook

1. **Load and Preview the Dataset**
   Examine the structure, columns, and data types.

2. **Check for Missing Values**
   Validate data completeness and integrity (no missing values detected).

3. **Filter High-Income Records**
   Isolate employees earning **>$100,000** to analyze advanced roles.

4. **Analyze and Visualize Trends**

   * Salary progression (2020 – 2024)
   * Average salaries by job title and experience
   * Salary distribution by company size and employment type

5. **Encode Categorical Variables**

   * Applied one-hot encoding and target encoding to prepare data for potential ML models.

---

## 📈 Results & Insights

* 📌 **Experience Level Impact:** Senior (SE) and Mid-level (MI) engineers earn significantly higher salaries.
* 📌 **Employment Type:** Full-time roles dominate among high earners.
* 📌 **Company Size:** Larger companies offer higher median salaries.
* 📌 **Geographic Trend:** Most high earners are based in the United States.
* 📌 **Salary Trend:** Consistent growth observed from 2020 to mid-2023, followed by a slight dip in 2024.

---

## 📚 References

* Kaggle.com – *Data Engineer Salary Dataset (2024)*
* Eric Matthes – *Python Crash Course: A Hands-On, Project-Based Introduction to Programming* (2015)

---

## 👩‍💻 Author

**Fatima Shamilova**

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 🫶 Acknowledgments

* *Kaggle community* – for open datasets supporting educational research.
* *Python open-source developers* – for maintaining invaluable analytical libraries.

1. None — DOI: file-CDLaVc4dm4Equ1kpidJxNv
2. None — DOI: file-7paHVTAgogCxejLJFHmWy8
