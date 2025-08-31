# PROGRAMMING LANGUAGE TRENDS — STACK OVERFLOW TAGS OVER TIME

This project explores the popularity of programming languages by analyzing **Stack Overflow** monthly tag counts.  
We analyze raw post counts, reshape the dataset into a time series, and smooth trends with rolling means.

## Objectives
- Load and inspect the Stack Exchange Data Explorer export.  
- Reshape to a time series of **monthly posts by language**.  
- Plot raw monthly series and a **6-month rolling mean**.  
- Rank languages by total posts across the entire period.

## Dataset
- **File:** `QueryResults.csv`  
- **Columns:**
  - `DATE` — month (e.g., 2008-09-01)  
  - `TAG` — programming language tag (e.g., `python`, `java`)  
  - `POSTS` — number of posts for that tag in the month  

> Note: Data can be exported fresh from [Stack Exchange Data Explorer](https://data.stackexchange.com/stackoverflow/query/675441/popular-programming-languages-per-over-time-eversql-com).

## Tools & Libraries
- **Python**  
- **Pandas** → data cleaning, reshaping, and rolling means  
- **Matplotlib** → visualizations  
- **Jupyter Notebook** (VS Code)  

## Analysis & Results
- **Most Popular Languages (by total posts):** historically dominated by Java, Python, JavaScript, C#, and PHP.  
- **Recent Trends:** Python shows consistent long-term growth, while others (e.g., Java, PHP) plateau or decline.  
- **Smoothing:** A 6-month rolling mean highlights clear trends by reducing monthly noise.  
- **Coverage Differences:** Some languages appear for fewer months (e.g., newer tags like Swift, Go).  

## Conclusion & Insights
- **Python** emerges as a clear long-term growth language on Stack Overflow.  
- **Legacy languages** like C and Java remain significant but show slower growth.  
- **Newer entrants** (Go, Swift) rise quickly, though total volumes are lower due to recency.  
- Tag-based analysis reflects developer community focus and can indicate real-world adoption trends.

This analysis shows how **community Q&A data** can reveal long-term shifts in programming language popularity.
