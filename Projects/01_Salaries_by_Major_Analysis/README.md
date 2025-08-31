# SALARIES BY COLLEGE MAJOR — EARNINGS, RISK & CAREER POTENTIAL

This project analyzes a dataset of **starting and mid-career salaries by U.S. college major**.  
The goal is to understand which majors offer the highest earnings, the most stability, and the greatest potential for growth.

## Objectives
- Identify the majors with the **highest starting salaries**.
- Find the majors with the **highest mid-career salaries**.
- Calculate **salary spread (P90 − P10)** to measure risk/reward.
- Compare broad groups (e.g., Business, STEM, Humanities).
- Visualize salary distributions for better insights.

## Dataset
- **File:** `salaries_by_college_major.csv`  
- **Columns:**
  - `Undergraduate Major`
  - `Starting Median Salary`
  - `Mid-Career Median Salary`
  - `Mid-Career 10th Percentile Salary`
  - `Mid-Career 90th Percentile Salary`
  - `Group` (broad field of study)


## Tools & Libraries
- **Python**
- **Pandas** → data cleaning & analysis
- **Matplotlib** → visualizations
- **Jupyter Notebook** (VS Code)

## Analysis & Results
- **Highest Starting Salary:** determined from `Starting Median Salary`.
- **Highest Mid-Career Salary:** determined from `Mid-Career Median Salary`.
- **Risk vs Reward:** `Spread = (Mid-Career 90th Percentile) − (Mid-Career 10th Percentile)`.
- **Group Comparisons:** aggregated averages by `Group`.
