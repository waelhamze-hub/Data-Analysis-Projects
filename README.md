# 📊 Salaries by College Major — Earnings, Risk & Career Potential

This project analyzes a dataset of **starting and mid-career salaries by U.S. college major**.  
The goal is to understand which majors offer the highest earnings, the most stability, and the greatest potential for growth.

---

## 🔹 Objectives
- Identify the majors with the **highest starting salaries**.
- Find the majors with the **highest mid-career salaries**.
- Calculate **salary spread (P90 − P10)** to measure risk/reward.
- Compare broad groups (e.g., Business, STEM, Humanities).
- Visualize salary distributions for better insights.

---

## 🔹 Dataset
- **File:** `salaries_by_college_major.csv`  
- **Columns:**
  - `Undergraduate Major`
  - `Starting Median Salary`
  - `Mid-Career Median Salary`
  - `Mid-Career 10th Percentile Salary`
  - `Mid-Career 90th Percentile Salary`
  - `Group` (broad field of study)

👉 Note: This dataset includes only **10th and 90th percentile salaries** (no 25th/75th percentiles in this version).

---

## 🔹 Tools & Libraries
- **Python**  
- **Pandas** → data cleaning & analysis  
- **Matplotlib** → visualizations  
- **Jupyter Notebook** (VS Code)  

---

## 🔹 Analysis & Results

### 💵 Highest Salaries
- **Highest Starting Salary:** Aerospace Engineering (~$57,700)  
- **Highest Mid-Career Salary:** Chemical Engineering (~$107,000)  

### ⚖️ Lowest Salaries
- **Lowest Starting Salary:** Spanish (~$34,000)  
- **Lowest Mid-Career Salary:** Education (~$52,000)  

### 📈 Risk vs Reward
- **Spread = P90 − P10 salaries**  
- Smaller spread = stable/low risk majors  
- Larger spread = majors with high-earning outliers (risky but rewarding)

---

## 🔹 Visualizations

### Top 10 Majors by Starting Salary
![Top 10 Starting Salaries](images/top_starting_salary.png)

### Distribution of Salary Spread
![Salary Spread Distribution](images/salary_spread_distribution.png)

---

## 🔹 Insights
- **STEM majors** (especially Engineering) dominate both starting and mid-career salaries.  
- **Humanities and Education** majors tend to have lower salaries throughout careers.  
- Some majors show **high spread** (large gap between top and bottom earners), which means higher risk/reward.  
- On average, **Engineering groups** lead in median salaries, while **Humanities lag behind**.  


