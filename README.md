# Code Champs by Country

This project analyzes a synthetic dataset spanning one hundred contests (1,000 placements) to identify which nationalities win the most often. Using Python in a Jupyter Notebook, it provides statistical insights and visualizations. A special focus is placed on Polish competitors and their performance over time.

## Features
- Aggregates and cleans contest results data
- Uses synthetic sample of top 10 placements across 100 contests and more than thirty nationalities
- Identifies top-performing nationalities
- Measures Polish representation and success
- Visualizes historical trends and country-level dominance

## Methodology
Win counts, top five, and top ten placements are calculated for each
country. A chi-square statistic tests whether win distribution differs
significantly among nations with similar economic output to Poland.

## Tech Stack
- Python
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
\nData is stored in `extended_contests_v2.csv` and is artificial due to offline restrictions.
