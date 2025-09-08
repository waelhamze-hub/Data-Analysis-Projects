# GOOGLE PLAY STORE — APPS & REVIEWS ANALYSIS

This project explores a dataset of **Android apps and reviews from the Google Play Store**.  
The goal is to understand app characteristics, market concentration, pricing, and download patterns.

## Objectives
- Clean and standardize raw app data (sizes, installs, pricing).
- Handle missing values and duplicates.
- Explore **ratings, reviews, installs, and sizes** across categories.
- Compare **free vs. paid apps**, including pricing strategies.
- Estimate potential revenues for paid apps.
- Visualize app market trends with **Plotly**.

## Dataset
- **File:** `apps.csv`  
- **Source:** [Kaggle — Google Play Store Apps](https://www.kaggle.com/lava18/google-play-store-apps)  
- **Columns include:**
  - `App` — App name  
  - `Category` — App category (e.g., Tools, Games, Education)  
  - `Rating` — Average user rating  
  - `Reviews` — Number of reviews submitted  
  - `Size` — App size (KB/MB/GB, converted to MBs)  
  - `Installs` — Number of installs (cleaned into numeric format)  
  - `Type` — Free or Paid  
  - `Price` — Price in USD (numeric)  
  - `Content Rating` — Age suitability  

## Tools & Libraries
- **Python**
- **Pandas / NumPy** → cleaning & transformation
- **Plotly Express** → interactive visualizations
- **Jupyter Notebook** (VS Code)

## Analysis & Results
- **Ratings**: Many top-rated apps have few reviews; reviews provide critical context.  
- **Installs**: Only a handful of apps reach **1B+ installs**; most apps have far fewer.  
- **App Size**: Sizes vary widely; games and multimedia apps are generally larger.  
- **Free vs Paid**: Free apps dominate downloads; most paid apps cost **under $10**.  
- **Revenue Estimates**: High-grossing paid apps are concentrated in specific categories.  

## Conclusion & Insights
- The Play Store exhibits a **winner-takes-most dynamic**: few apps capture most installs and revenue.  
- **Category selection matters**: Tools, Games, and Communication lead downloads.  
- **Pricing strategy is crucial**: low-cost paid apps perform better than high-priced outliers.  
- **Developers** should align app size, category, and monetization model with user expectations.  

This analysis highlights both **market opportunities** and the **competitive challenges** in the Android ecosystem.
