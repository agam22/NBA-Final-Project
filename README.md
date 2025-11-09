 Evolution of NBA Playing Styles — Data Science Final Project
Data Science Workshop — Final Project

Instructor: Dr. Idan Alter

 Project Overview

This project explores how the NBA has changed over time — both tactically and statistically — through the lens of data science.
We analyze multi-era datasets containing advanced player metrics, team shot distributions, and league-wide trends to reveal the transformation of basketball from traditional, mid-range oriented play to the modern, positionless, perimeter-focused game.

Our goal is not only to visualize trends but also to provide quantitative evidence for key shifts in the NBA’s evolution.

 Objectives

Identify major structural and stylistic changes in NBA play since the 1970s.

Quantify the rise of three-point shooting and spacing.

Analyze changes in player roles and the decline of rigid positional boundaries.

Use statistical and visualization tools to tell a coherent “story” of basketball evolution.

 Datasets

We used multiple complementary CSV files (compiled and cleaned within the notebook):

File	Description
Advanced.csv	Player-level advanced metrics (TS%, BPM, USG%, etc.) for all seasons.
league_season_summary.csv	League-wide averages and shooting profiles per season.
shots_sampled.csv	Sampled shot distances for spatial analysis and distribution modeling.
team_season_3pt_share.csv	Team-level 3P attempt share by season.
(optional) totals.csv	Aggregated totals used for historical pace/efficiency normalization.
 Methodology

Data Cleaning & Preparation

Standardized season formats (e.g., 1998–99 → 1999).

Removed missing or non-numeric entries.

Normalized key statistics (per 100 possessions, pace-adjusted).

Exploratory Data Analysis (EDA)

Visualized trends in shot distance, efficiency (TS%), and positional metrics.

Compared eras and roles using boxplots, moving averages, and correlation matrices.

Research Questions

When did “positionless basketball” truly emerge?

How did the shift in shot selection affect efficiency?

Did big men evolve into playmakers?

What statistical signals mark the modern era of basketball?

Modeling & Statistical Tools

Trend regressions, correlation analysis, and hypothesis testing.

Python libraries: pandas, numpy, matplotlib, seaborn, statsmodels.

 Key Findings

The three-point revolution began slowly after 1979 but accelerated post-2010.

Mid-range shots collapsed as spacing and efficiency metrics (TS%) rose in parallel.

Positional roles blurred, evidenced by assist percentages and usage convergence across positions.

League-wide offensive ratings reached historical peaks — statistically linked to changes in shot mix.

 Technologies Used

Python (3.12)

Jupyter / Google Colab

pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels

Optional integration with nba_api and pbpstats for further extensions.

 Deliverables

Rendered Notebook (.html or nbviewer link)

Recorded Presentation (10–20 min) — screen + voice explanation of the notebook and findings.

Links to datasets and references

Personal reflection summary

 Future Work

Extend analysis to play-by-play spatial data to measure spacing indices.

Incorporate defensive metrics to balance the offensive focus.

Apply unsupervised learning (clustering or PCA) to group similar player archetypes across eras.

 Authors

Agam Yehuda
