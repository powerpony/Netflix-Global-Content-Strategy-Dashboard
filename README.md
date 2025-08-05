# Netflix-Global-Content-Strategy-Dashboard
An interactive Tableau dashboard exploring Netflix’s global content trends by genre, country, and rating.

## Problem Statement

How has Netflix’s content strategy evolved globally over time in terms of content type, genre, country, and audience rating — and what insights can help guide future content acquisition and personalization strategies?

This project explores global trends using a cleaned and normalized version of Netflix’s public content catalog, visualized in an interactive Tableau dashboard.

## Tools Used

- Python (Pandas): Data cleaning and preprocessing  
- Tableau: Data visualization and interactive dashboard  
- Jupyter Notebook: For exploration and normalization  
- GitHub: For documentation and version control

---

## Key Insights

-  Content growth peaked in 2019 with over 2,000 titles added, before slowing down post-2020.
-  The United States dominates Netflix’s catalog, but international content is rising rapidly — e.g., *“International Movies”* make up ~29% of total titles.
-  Dramas and comedies are the most prevalent genres, but there's a growing presence of niche categories like documentaries and stand-up.
-  TV-MA and TV-14 ratings account for over 50% of all content — indicating a strategy focused on mature and older teen audiences.
-  Titles span 87 countries, with significant content contributions from India, the UK, Canada, and South Korea — supporting regional production and localization.

---

## Data Cleaning Process

- Dropped rows with missing country or genre metadata  
- Split multi-value fields (country, listed_in) into individual rows via explode()  
- Standardized naming (e.g., “West Germany” → “Germany”, “Soviet Union” → “Russia”)  
- Final cleaned dataset saved as netflix_normalized.csv

---

## Files Included

| File | Description |
|------|-------------|
| netflix_titles.csv | Original dataset (Kaggle, Shivam Bansal) |
| netflix_normalized.csv | Cleaned and exploded dataset |
| netflix.py | Python script for preprocessing |
| Netflix Global Content Strategy Dashboard.twbx | Tableau packaged workbook |
| README.md | Project overview and insights |

---

## Live Dashboard

Link: [View on Tableau Public](https://public.tableau.com/app/profile/divya.kalaichelvan/viz/NetflixGlobalContentStrategyDashboard/Dashboard1)

---

## Author

Divya Kalaichelvan  
Aspiring data analyst | CS student | Driven by storytelling through data

---

## Updates

- Project may be updated with extended analyses (e.g., clustering genres or recommendation systems)
