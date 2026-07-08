# Zomato Restaurants — Exploratory Data Analysis

## Overview
An exploratory data analysis of the Zomato Restaurants dataset, examining restaurant 
ratings, pricing, cuisines, and delivery patterns across cities. Built as Project 01 
for the Pluto Academy AI/ML Internship Program.

## Dataset
- **Source:** [Zomato Restaurants Dataset](https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data) (Kaggle)
- **Size:** 9,551 restaurants across 15 countries
- **Fields used:** City, Cuisines, Average Cost for two, Price range, Aggregate rating, 
  Votes, Has Online delivery, Has Table booking

## Tools & Libraries
- Python
- Pandas & NumPy — data cleaning and analysis
- Matplotlib & Seaborn — visualizations
- Google Colab — development environment

## Process
1. **Data Cleaning** — dropped near-constant columns, removed rows with missing core 
   metadata, deduplicated by Restaurant ID, separated unrated (0.0) restaurants from 
   rating-based analysis
2. **Exploratory Analysis** — answered 5 questions on city ratings, delivery impact, 
   cost by price range, cuisine popularity vs. rating, and table booking's effect on votes
3. **Visualization** — 6 charts (bar, histogram, scatter, pie, heatmap, line)
4. **Insights** — 5 data-backed findings documented in the notebook

## Key Insights
- London tops city ratings (4.54 avg) among cities with 20+ restaurants
- Restaurants with online delivery average *lower* ratings (3.38) than those without 
  (3.47), despite higher vote counts — delivery drives engagement, not satisfaction
- Average rating rises steadily with price range, from 3.3 to 3.9
- North Indian is the most common cuisine (2,208 restaurants) but ranks near the bottom 
  in average rating (3.25) among top cuisines
- Restaurants with table booking average more than double the votes of those without 
  (368 vs. 173)

Full write-up with supporting charts is in the notebook.

## How to Run
1. Open `Zomato_EDA.ipynb` in Google Colab
2. Upload `zomato.csv` (from the Kaggle dataset link above) when prompted
3. Run all cells

## Links
- **Colab Notebook:** [https://colab.research.google.com/drive/18N7LhbkQhxo1JZ6OScGTMxW5y6zLp8yd?usp=sharing]
- **Author:** [Varshini Gujju] — [https://github.com/varshini3406]
