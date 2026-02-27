# 📊 Data Job Market Analysis – Germany Focus

## 📌 Overview

This project explores the data job market in **Germany**, with a primary focus on **Data Analyst roles**.  

The objective is to understand:

- Which skills are most in demand  
- How skill demand is trending  
- Which skills command higher salaries  
- What the most optimal skills are (High Demand + High Pay)

The dataset is sourced from Luke Barousse’s Python course and contains detailed information on job titles, salaries, job locations, and required skills. Using Python, I performed structured exploratory analysis and built visualizations to extract actionable insights.

---

## ❓ Key Questions

1. What are the most demanded skills for the top 3 most popular data roles in Germany?
2. How are in-demand skills trending for Data Analysts?
3. How well do jobs and skills pay for Data Analysts?
4. What are the most optimal skills to learn (High Demand & High Paying)?

---

## 🛠 Tools & Technologies Used

- **Python**
- **Pandas** – Data cleaning & aggregation
- **Matplotlib** – Core visualizations
- **Seaborn** – Statistical visualizations
- **Hugging Face Datasets** – Data loading
- **Jupyter Notebook**
- **VS Code**
- **Git & GitHub**

---

## 🧹 Data Preparation

Key preprocessing steps:

- Converted `job_posted_date` to datetime format
- Cleaned `job_skills` using `ast.literal_eval`
- Filtered dataset to Germany
- Exploded skill lists for skill-level analysis

---

# 📈 Analysis & Findings

---

## 1️⃣ Most Demanded Skills (Top 3 Roles)

### Method
- Identified top 3 most common job titles in Germany
- Calculated skill counts per role
- Extracted top 5 skills per role
- Visualized using horizontal bar charts

### Insights
- SQL remains foundational across multiple roles.
- Python is critical for Data Scientists and Data Engineers.
- Data Engineers require more cloud and infrastructure tools.
- Data Analysts rely more on BI and reporting tools.

---

## 2️⃣ Trending Skills for Data Analysts (2023)

### Method
- Filtered Data Analyst roles
- Grouped skills by posting month
- Calculated monthly percentage demand
- Visualized using line plots

### Insights
- SQL remains consistently dominant.
- Excel shows increasing demand later in the year.
- Python and Tableau remain stable and essential.
- BI tools show gradual upward adoption.

---

## 3️⃣ Salary Analysis

### A) Salary Distribution by Role

Used boxplots to compare salary distributions of major roles.

**Insights:**
- Senior roles command significantly higher salaries.
- Data Engineers and Data Scientists show wider salary variance.
- Data Analysts show more stable salary ranges.

---

### B) Highest Paid vs Most In-Demand Skills (Data Analysts)

Two separate bar charts were used to show:

- Top 10 highest paying skills
- Top 10 most in-demand skills

**Insights:**
- Specialized tools command higher pay.
- Foundational tools (Excel, SQL) dominate demand.
- Clear distinction between high-demand and high-pay skills.

---

## 4️⃣ Optimal Skills (High Demand + High Pay)

### Method
- Calculated skill demand percentage
- Calculated median salary per skill
- Built scatter plot (Demand vs Salary)

### Insights
- Python, SQL, and Tableau sit in strong demand + strong salary zone.
- Some niche database skills command high salaries despite lower demand.
- Programming and database skills cluster at higher salary levels.

---

# 🎯 What I Learned

- Real-world datasets often contain mixed data types requiring careful cleaning.
- Skill demand and salary are correlated but not identical.
- Data visualization design significantly impacts clarity of insights.
- Strategic skill development requires balancing demand and earning potential.

---

# 💡 Strategic Takeaways

- SQL is essential for data roles.
- Python is a high-leverage skill across roles.
- BI tools increase employability.
- Cloud & infrastructure skills increase earning potential.
- Combining foundational and specialized skills maximizes career value.

---

# 🚀 Conclusion

This project provides a structured, data-driven exploration of the German data job market.

By analyzing demand trends, salary distributions, and skill intersections, the project delivers practical insights for:

- Aspiring Data Analysts
- Career switchers
- Professionals planning skill development
- Anyone navigating the data job market

The findings reinforce the importance of combining strong foundational tools (SQL, Excel) with high-impact technical skills (Python, Cloud, BI).

---

## 📂 Repository Structure

- 📘 [1_Basics](https://github.com/nitinsinghdm/Python_Data_Project/tree/main/1_Basics)  
  → Core Python concepts (data types, loops, functions, libraries, data cleaning)

- 🚀 [2_Advanced](https://github.com/nitinsinghdm/Python_Data_Project/tree/main/2_Advanced)  
  → Advanced Pandas, grouping, aggregation, and visualization techniques

- 📊 [3_Project](https://github.com/nitinsinghdm/Python_Data_Project/tree/main/3_Project)  
  → Real-world data job market analysis (Germany-focused)

---

## ⭐ Final Note

This project reflects my practical application of Python, data cleaning, aggregation, and visualization techniques to real-world labor market data.

As the data landscape evolves, continuous analysis and skill development remain essential — and this project serves as a foundation for deeper analytical exploration.