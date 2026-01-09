# Project 2: Video Game Sales — Exploratory Data Analysis (EDA)

## Overview
This project presents an exploratory data analysis of global video game sales data with the goal of identifying long-term trends, platform lifecycles, genre performance, and regional market differences.

The analysis focuses on understanding how video game sales evolved over time, which platforms and genres dominated the market, and how regional preferences shaped global sales patterns.

---

## Dataset
**Video Game Sales Dataset (`vgsales.csv`)**

The dataset includes historical sales data for video games, covering:
- Game title
- Platform
- Genre
- Publisher
- Release year
- Regional sales (North America, Europe, Japan, Other)
- Global sales

---

## Objectives
- Explore historical trends in global video game sales
- Identify top-performing platforms, genres, and publishers
- Analyze regional differences in video game consumption
- Understand lifecycle patterns of console generations

---

## Files
- `vgsales.csv` — raw dataset containing global video game sales data  
- `video_game_sales_eda_2_done.ipynb` — Jupyter Notebook with full EDA, visualizations, and insights

---

## Analysis Workflow
The analysis was conducted using a structured EDA approach:

1. **Data Inspection & Cleaning**
   - Initial exploration of dataset structure
   - Handling missing values and inconsistent entries
   - Data type corrections

2. **Univariate Analysis**
   - Distribution of global sales
   - Frequency analysis of platforms, genres, and publishers

3. **Multivariate Analysis**
   - Sales comparison across platforms and genres
   - Publisher performance analysis
   - Regional sales contribution breakdown

4. **Temporal Analysis**
   - Evolution of video game sales over time
   - Identification of peak market periods
   - Platform lifecycle patterns across console generations

5. **Regional Analysis**
   - Comparison of North America, Europe, and Japan markets
   - Identification of region-specific preferences

---

## Key Insights
- Video game sales show clear cyclical patterns driven by console generation lifecycles
- A small number of platforms account for a disproportionately large share of global sales
- Action and Sports genres consistently dominate global sales volumes
- Regional markets differ significantly, with Japan exhibiting distinct platform and genre preferences
- Market saturation and decline phases are observable after peak platform adoption

---

## Tools & Technologies
- **Python**
- **Pandas** — data manipulation and aggregation
- **Matplotlib & Seaborn** — data visualization
- **Jupyter Notebook** — exploratory analysis environment

---

## Conclusion
This analysis highlights how historical video game sales are shaped by platform innovation cycles, genre popularity, and regional market behavior. The findings provide a strong foundation for deeper predictive modeling or market segmentation analysis in future work.
