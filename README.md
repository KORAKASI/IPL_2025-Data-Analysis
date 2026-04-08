# IPL 2025 Ball-by-Ball Data Analysis
### Web Scraping | Data Cleaning | Exploratory Data Analysis (EDA)

## Project Overview
This project presents an end-to-end data analytics pipeline built on ball-by-ball data from the Indian Premier League 2025. The objective is to transform raw, unstructured cricket data into meaningful insights using web scraping, data preprocessing, and exploratory data analysis techniques.

## Problem Statement
Cricket match data available on platforms like ESPN Cricinfo is unstructured and not analysis-ready.

## Key challenges include:
Inconsistent data formats (score strings, player names)
Lack of structured datasets for analysis
Hidden insights in large ball-by-ball datasets

This project solves these challenges by building a structured analytical dataset and extracting actionable insights.

## Tech Stack
Programming: Python

Web Scraping: Requests, BeautifulSoup

Data Processing: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Environment: Jupyter Notebook

## Project Workflow
Web Scraping → Data Cleaning → Feature Engineering → EDA → Insights

- **Web Scraping**

Extracted ball-by-ball data (70 matches, ~16K+ deliveries)
Source: ESPN Cricinfo
Captured features like batter, bowler, runs, overs, toss, venue
- **Data Cleaning & Transformation**

Converted data types (date, score)
Parsed score into:
Bat_runs
Extras
Wickets
Standardized team & player names
Created new features:
Total_runs
Match Phases (Powerplay, Middle, Death)
- **Exploratory Data Analysis**

Univariate, Bivariate, Multivariate analysis
Correlation analysis between variables
Phase-wise performance evaluation

- **Key Insights**

- Batting Dominance

Bat_runs show strong correlation (~0.98) with Total_runs
Batting performance is the primary driver of match outcomes
- Match Phase Analysis

Middle Overs (7–15) contribute the highest runs
Most wickets also fall in middle overs → critical phase

- Scoring Patterns

Majority of deliveries yield 0–2 runs
Boundaries are less frequent but high impact

- Team Performance

Punjab Kings leads in total runs and scoring efficiency
Mumbai Indians and Gujarat Titans show consistent performance

- Toss Impact

Toss advantage is not a strong determinant of match outcomes

- Visualizations
  
Distribution of runs per ball
Stadium-wise match distribution
Phase-wise analysis (Powerplay, Middle, Death)
Correlation heatmaps
Team performance comparisons

- Limitations
  
Some match data not available during scraping
Dependent on external website structure (ESPN Cricinfo)
Analysis is descriptive (no predictive modeling)

## Future Enhancements
Build predictive models (match outcome, player performance)

Develop interactive dashboards (Power BI / Tableau)

Deploy as a web app (Streamlit)

Automate real-time data pipeline
