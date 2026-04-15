# Netflix Analytics Dashboard

An interactive content analytics dashboard built on Netflix data using Power BI, DAX, and Power Query.

![Dashboard Preview](Screenshots/Dashboard.png)

---

## Overview

This project performs end-to-end ETL and visual analysis on a Netflix dataset to uncover content trends, genre distributions, rating breakdowns, and release patterns across years. The dashboard is designed for interactive exploration with cross-filtering and slicers.

---

## Features

- ETL pipeline using Power Query to clean, transform, and shape raw CSV data
- 10+ interactive visualizations including bar charts, donut charts, maps, and trend lines
- DAX-calculated measures for KPIs: total titles, average rating, content growth rate
- Cross-filter interactivity — clicking any visual filters the entire report page
- Slicers for Type (Movie / TV Show), Genre, Country, and Year
- Content breakdown by country of origin using a filled map visual

---

## Tech stack

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard design and publishing |
| Power Query (M language) | Data cleaning and transformation |
| DAX | Calculated columns and measures |
| SQL | Initial data querying and exploration |

---

## Dataset

- Source: Netflix Movies and TV Shows dataset (publicly available on Kaggle)
- Records: ~8,800 titles
- Fields used: title, type, director, cast, country, date_added, release_year, rating, listed_in, duration

---

## Key insights from the dashboard

- Movies make up ~70% of Netflix's catalog vs TV shows
- United States, India, and United Kingdom are the top 3 content-producing countries
- Content additions peaked between 2018–2020
- Drama, International Movies, and Comedies are the top 3 genres
- TV-MA is the most common content rating

---

## How to open

1. Download the `.pbix` file from this repo
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Interact with the slicers and visuals on each page

---

## Screenshots

| Index Page |  Suggestion |
|---|---|
| ![Index](Screenshots/Index.png) | ![Suggestion](Screenshots/Suggestion.png) |

> Add your own screenshots to the `/screenshots` folder after exporting from Power BI (File → Export → PNG)

---

## Project structure

```
netflix-analytics-dashboard/
├── netflix_dashboard.pbix       # Main Power BI file
├── data/
│   └── netflix_titles.csv       # Raw dataset
├── screenshots/
│   ├── dashboard.png
│   ├── overview.png
│   └── genre.png
└── README.md
```

---

## Author

**Kishore S** — [LinkedIn](https://linkedin.com/in/kishore-sakthi) · [GitHub](https://github.com/Kishore-june)
