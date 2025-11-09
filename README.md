#  Evolution of NBA Playing Styles  
### *Data Science Final Project – Open University of Israel*  
Instructor: **Dr. Idan Alter**

---

##  Overview

This project investigates **how the NBA has evolved over the decades** — from mid-range heavy offenses and rigid positions to today’s **positionless, three-point-driven game**.

Through data-driven storytelling, we explore:
- the rise of three-point shooting,  
- the fall of mid-range play,  
- and the statistical convergence between guards, forwards, and centers.

Our analysis blends **data cleaning**, **EDA**, **mathematical modeling**, and **visual analytics** to reveal the league’s structural evolution.

---

##  Project Objectives

1. **Quantify** the stylistic shifts in NBA play since the 1970s.  
2. **Visualize** changes in shooting profiles and spacing.  
3. **Measure** the evolution of player roles and positional fluidity.  
4. **Demonstrate** data-science techniques to tell a cohesive story of basketball’s transformation.

---

##  Datasets

| File | Description |
|------|--------------|
| `Advanced.csv` | Player-level advanced metrics (TS%, BPM, USG%, etc.) per season. |
| `league_season_summary.csv` | League-level summaries — offensive pace, efficiency, and shot zones. |
| `shots_sampled.csv` | Sampled shot distances for distribution and spatial analysis. |
| `team_season_3pt_share.csv` | Team-level share of 3-point attempts by season. |


Each dataset contributes to a unified narrative of **efficiency, volume, and positional change**.

---

##  Methodology

### 1. Data Cleaning & Preprocessing
- Standardized season formats (`1998-99 → 1999`)  
- Removed missing / invalid rows  
- Normalized metrics (e.g., per 100 possessions)

### 2. Exploratory Data Analysis (EDA)
- Trends in **shot distance**, **True Shooting %**, and **3-point rate**  
- Comparison by **era** and **position**  
- Correlation and variance analysis to detect role convergence

### 3. Research Questions
-  *When did “positionless basketball” truly emerge?*  
-  *How did shot selection shifts drive scoring efficiency?*  
-  *Did big men evolve into playmakers?*  
-  *What quantitative signals define the modern NBA?*

### 4. Statistical Tools
- Correlation & regression analysis  
- Moving averages and trend modeling  
- Variance reduction tests between positions  

Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `scikit-learn`

---

##  Key Findings

-  **Three-point volume skyrocketed** post-2010, reshaping spacing and pace.  
-  **Mid-range shots collapsed**, replaced by rim and perimeter efficiency.  
-  **Positional boundaries blurred**, with forwards and centers taking on guard-like roles.  
-  Statistical modeling confirms that **shot mix alone** explains much of the rise in league-wide TS%.  

---

##  Technologies Used

| Category | Tools |
|-----------|-------|
| Programming | Python 3.12 |
| Environment | Jupyter / Google Colab |
| Data Libraries | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Modeling | statsmodels, scikit-learn |

---

##  Deliverables

-  **Rendered Notebook** 
-  **Recorded Presentation (10–20 min)** explaining the notebook and findings  
-  **Data Links** to all used datasets  
-  **Personal Reflection Summary** — project experience & insights

---

##  Future Work

- Integrate **play-by-play spatial data** to calculate spacing indices.  
- Include **defensive metrics** for a holistic efficiency model.  
- Use **PCA or clustering** to identify player archetypes across eras.  

---

##  Author

**Agam Yehuda**   

---

