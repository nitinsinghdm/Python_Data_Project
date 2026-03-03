# 📊 Data Job Market Analysis – Germany (Exploratory Data Analysis Project)

## 📌 Overview

This project performs structured **Exploratory Data Analysis (EDA)** on a large-scale global job postings dataset (50k+ records), with a focused analysis of **Data Analyst roles in Germany**.

The objective is to explore labor market demand, analyze salary patterns, and identify optimal skill combinations based on both demand and compensation.

This project demonstrates practical application of Python for real-world data cleaning, transformation, aggregation, visualization, and insight extraction.

---

## 🎯 Key Questions

- What are the most demanded skills for the top data roles?
- How are in-demand skills trending for Data Analysts in Germany?
- How do salaries vary across roles and skills?
- Which skills are both high-demand and high-paying for Data Analysts?

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas** – Data cleaning, transformation, aggregation
- **Matplotlib** – Core visualizations
- **Seaborn** – Statistical visualizations
- **Hugging Face Datasets** – Data loading
- **Jupyter Notebook**
- **Git & GitHub**

---

## 🧹 Data Preparation & Cleaning

Key preprocessing steps:

- Converted `job_posted_date` to datetime format
- Parsed nested skill lists using `ast.literal_eval`
- Filtered dataset for Germany-specific roles
- Exploded skill lists for skill-level frequency analysis
- Handled missing and mixed data types

These steps ensured structured and reliable analysis.

---

## 📊 Exploratory Data Analysis (EDA)

### 1️⃣ Job Distribution Analysis

- Compared job counts by role globally
- Analyzed country-level job distribution
- Identified Data Analyst, Data Engineer, and Data Scientist as the most frequent roles
- Narrowed focus to Germany-specific Data Analyst roles

**Insight:**  
Data Analyst roles show strong demand globally, with Germany ranking among active hiring markets.

---

### 2️⃣ Skill Demand Analysis (Germany – Data Analyst)

- Calculated skill frequency counts
- Analyzed monthly skill demand trends
- Compared foundational vs specialized tools

**Key Findings:**

- SQL remains consistently dominant
- Python and Tableau show stable demand
- Excel remains relevant in Data Analyst roles
- BI tools show gradual adoption growth

---

### 3️⃣ Salary Analysis

- Compared salary distributions across major data roles
- Analyzed salary variance and median differences
- Identified highest-paying skills vs most in-demand skills

**Insights:**

- Senior roles command significantly higher salaries
- Specialized tools command higher pay
- Foundational tools dominate demand but not always salary

---

### 4️⃣ Optimal Skill Identification (Demand vs Salary)

- Calculated skill demand percentages
- Computed median salary per skill
- Built demand vs salary scatter analysis

**Key Finding:**  
Python, SQL, and Tableau sit in the strong demand + strong salary zone in Germany.

---

## 🚀 Project Structure

### 📘 Python Fundamentals
Core Python concepts and data handling exercises:

👉 https://github.com/nitinsinghdm/Python_Data_Project/tree/main/1_Basics

---

### 🚀 Advanced Pandas & Visualization
Advanced data manipulation, grouping, aggregation, and visualization techniques:

👉 https://github.com/nitinsinghdm/Python_Data_Project/tree/main/2_Advanced

---

### 📊 Germany-Focused EDA Project
Complete exploratory analysis of the German data job market:

👉 https://github.com/nitinsinghdm/Python_Data_Project/tree/main/3_Project

---

## 💡 Strategic Takeaways

- SQL is foundational for Data Analyst roles
- Python increases earning potential
- BI tools improve employability
- Specialized database or cloud tools increase salary ceilings
- Skill demand and salary are correlated but not identical

---

## 🎯 Conclusion

This project demonstrates practical, structured **Exploratory Data Analysis (EDA)** applied to real-world labor market data.

It reflects competency in:

- Data cleaning
- Aggregation and transformation
- Trend analysis
- Visualization
- Business interpretation

The findings provide actionable insights for professionals navigating the German data job market.
