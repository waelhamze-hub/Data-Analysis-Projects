# LEGO DATA ANALYSIS — SETS, THEMES & TRENDS

This project explores LEGO datasets from **Rebrickable** to understand how LEGO sets and themes evolved over time, which themes dominate, and whether sets have become larger and more complex.

## Objectives
- Identify the **largest LEGO sets** by number of parts.  
- Discover the **first LEGO sets released** and how many products were offered in early years.  
- Track the **growth of LEGO sets and themes year by year**.  
- Analyze whether the **average number of parts per set** has increased over time.  
- Find which **themes have the most sets** (licensed vs original).  

## Dataset
- **Source:** [Rebrickable](https://rebrickable.com/downloads/)  
- **Files:**
  - `data/colors.csv` — LEGO colors and transparency info  
  - `data/sets.csv` — list of LEGO sets, year released, number of parts, theme ID  
  - `data/themes.csv` — mapping of theme IDs to theme names  

- **Columns (sets.csv):**
  - `set_num` — unique set identifier  
  - `name` — LEGO set name  
  - `year` — release year  
  - `theme_id` — links to `themes.csv`  
  - `num_parts` — number of parts in the set  

## Tools & Libraries
- **Python**  
- **Pandas** → data cleaning, grouping, aggregation  
- **Matplotlib** → visualizations (line, scatter, bar charts)  
- **Jupyter Notebook** (VS Code)  

## Analysis & Results
- **Largest sets:** The biggest LEGO sets by parts are easily identified (e.g., Star Wars and large collector sets).  
- **First sets:** LEGO’s first sets were released in 1949 with just a handful of products.  
- **Growth over time:** Number of sets and themes released increased significantly in later decades.  
- **Complexity:** Average parts per set show a clear upward trend, indicating sets became more detailed over time.  
- **Top themes:** Certain themes (e.g., Star Wars) dominate in number of sets compared to others.  

## Conclusion & Insights
- LEGO expanded dramatically in both **sets** and **themes**, especially after the 1980s.  
- The **average LEGO set has grown in complexity**, with more parts per set over time.  
- **Licensed themes** like Star Wars and Harry Potter have become some of the largest product lines.  
- LEGO’s strategy shifted from a small range of simple products to a **broad and diverse catalog** appealing to different age groups and interests.  

This analysis highlights LEGO’s evolution from a small toy maker to a global brand with an ever-expanding universe of sets and themes.
