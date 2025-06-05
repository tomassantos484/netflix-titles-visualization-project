# 🎥 Netflix Titles Visualization Project (Tableau)

This project uses Tableau to explore Netflix's content catalog using the [netflix_titles.xlsx](https://www.kaggle.com/datasets/shivamb/netflix-shows) dataset from Kaggle. The goal is to analyze content patterns by type, geography, genre, rating, and duration.

---

## 💡 Objective
Develop three interactive dashboards in Tableau to help Netflix understand its global content strategy and catalog trends.

---

## 🔹 Dataset
- **Source**: Kaggle
- **File**: `netflix_titles.xlsx`
- **Fields** include: `type`, `title`, `country`, `date_added`, `rating`, `duration`, `listed_in`, `cast`, `director`

---

## 📊 Dashboards Overview

### ✅ **Dashboard 1: Content Overview**
- **Total Titles by Type**: Bar chart comparing Movies vs. TV Shows
- **Content Growth Over Time**: Line chart showing annual additions (by `date_added`)
- **Top Countries by Content Volume**: Filled map visualizing title count by country
- **Top 10 TV Ratings**: Bar chart of the most common audience ratings
- **Top Genres**: Bar chart showing the most frequent genres in Netflix's library

### ✅ **Dashboard 2: Geographic Trends & Content Type**
- **TV vs. Movie by Country**: Stacked bar chart by country
- **TV Rating Distribution Across Countries**: Bubble chart by rating and country
- **Content Types by Rating**: Stacked bar chart by rating and type
- **Genre Diversity by Country**: Bubble chart showing unique genres per country
- **Title Additions Over Time (Top 5 Countries)**: Line chart colored by country

### ✅ **Dashboard 3: Ratings & Audience Analysis**
- **Global Rating Distribution**: Bar chart by rating
- **Content Type by Rating**: Stacked bar chart
- **Top Ratings in the U.S.**: Filtered bar chart (country = United States)
- **Distribution of Movie Durations**: Histogram in minutes
- **Distribution by Content Type**: Box plot comparing duration in minutes (Movies) vs. seasons (TV Shows)

---

## 🌐 Interactivity
- Slicers/filters added:
  - Content Type (Movie / TV Show)
  - Country
  - Rating
  - Genre
  - Year Added
  - Movie Duration (Range)
  - TV Show Seasons (Range)

---

## 📁 Files
- `Netflix_Titles_Visualization.twbx` — Tableau Packaged Workbook
- `netflix_titles.xlsx` — Raw dataset used

---

## 🎓 How Did I Make This?
- Tableau Desktop (Visualizations & Dashboarding)
- Power Query (Data Cleaning)
- Calculated Fields & Parameters

---

## 🚀 How to Use
1. Download `Netflix_Titles_Visualization.twbx`
2. Open `Netflix_Titles_Visualization.twbx` in Tableau Desktop
3. Explore each dashboard and adjust filters for interactivity!

---

## 🚀 Insights
- TV-MA is the most common global rating, followed by TV-14 and TV-PG.
- The United States, the United Kingdom, and India dominate Netflix's catalog volume.
- Titles added peaked in 2019 before dropping in 2020 due to COVID-19.
- Movies average 107 minutes, while TV Shows have a median of 6 seasons.

---

## 📸 Dashboards In Action
<img width="1295" alt="Screenshot 2025-06-05 at 12 52 29 AM" src="https://github.com/user-attachments/assets/843ec814-ff16-440e-a023-7d56665e3df1" />


<img width="1291" alt="Screenshot 2025-06-05 at 12 52 40 AM" src="https://github.com/user-attachments/assets/f5beb17f-1297-4b00-9362-ddcc0a2b6c69" />


<img width="1291" alt="Screenshot 2025-06-05 at 12 52 50 AM" src="https://github.com/user-attachments/assets/f6de5c84-b983-444d-9749-b64ddb758577" />

