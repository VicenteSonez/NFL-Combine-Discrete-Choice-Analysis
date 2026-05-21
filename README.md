# NFL Combine Discrete Choice Analysis

## Overview
This repository contains a comprehensive Exploratory Data Analysis (EDA) and econometric modeling of the NFL Scouting Combine data from 2010 to 2023. The main objective is to understand how physical traits and athletic performance metrics influence a player's probability of being drafted into the NFL, using **Discrete Choice Models**.

This project was developed for the Understanding Consumer Behavior through Discrete Choice Models course, taught by Sebastián Astroza.

## 📊 Features & Analysis
- **Extensive EDA:** Deep dive into 4,700+ combine participants, exploring missing values, distribution of athletic metrics, and differences between drafted and undrafted players.
- **Position-Specific Standardization:** Since athletic metrics are highly dependent on player positions (e.g., a 4.90s 40-yard dash is fast for an Offensive Tackle but slow for a Wide Receiver), all metrics were standardized using intra-position Z-scores.
- **Econometric Modeling:** 
  - **Binary Logit Model:** Predicting whether a player gets drafted or goes undrafted.
  - **Nested Logit Model:** A hierarchical choice model accounting for the draft round (Early Rounds, Late Rounds) vs. Undrafted, solving the Independence of Irrelevant Alternatives (IIA) assumption.

## 📂 Project Structure
- `EDA_nfl_combine.ipynb`: The primary notebook containing data cleaning, visualizations, position-based standardization, and exploratory insights.
- `Nested_Logit_NFL_Draft.ipynb`: The modeling notebook where the Multinomial and Nested Logit models are estimated using `pylogit`.
- `nfl_combine_cleaned.csv`: The preprocessed dataset ready for choice model estimation.
- `walkthrough.md`: A detailed report summarizing the statistical findings and visual distributions.

## 🛠️ Tools Used
- Python (`pandas`, `numpy`, `matplotlib`, `seaborn`)
- `pylogit` for Discrete Choice Modeling
- `scipy` for statistical testing (Likelihood Ratio Test)
