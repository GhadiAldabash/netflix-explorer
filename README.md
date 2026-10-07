<div align="center">

# Netflix Content Explorer

### An Interactive Netflix Content Analytics Dashboard

[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)

**[Open the Live App](https://netflix-explorer-gkrqjukdz7k8xpcck4jtxy.streamlit.app)**

</div>

---

## Overview

An interactive analytics dashboard built with **Streamlit** to explore and analyze a catalog of **1,040 Netflix titles** - spanning movies, series, documentaries, and more. The app is styled with Netflix's signature visual identity (red & black) and powered by interactive Plotly visualizations and dynamic filters.

---

## Features

- **Netflix-branded design** - a dark red-and-black theme with the Netflix logo and polished typography.
- **Interactive sidebar filters**: release year, language, genre, content type, and age rating.
- **Live KPIs**: total titles, Netflix Originals, average IMDb rating, number of languages, and average duration.
- **Interactive charts** across 4 tabs:
  - **Overview** - distribution by decade, content-type mix, duration bands, and Originals vs. Licensed.
  - **Genres & Ratings** - top genres, content ratings, and IMDb score distribution.
  - **Global** - distribution by language, a country-of-origin world map, and a genre-by-decade heatmap.
  - **Browse Titles** - a searchable, sortable table with CSV export of the filtered data.
- **Search, sort, and export** titles to CSV.

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| **Python** | Core programming language |
| **Streamlit** | Interactive web interface |
| **Pandas & NumPy** | Data processing & analysis |
| **Plotly** | Interactive visualizations |
| **HTML/CSS** | Custom styling & theming |

---

## Run Locally

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Launch the app
streamlit run app.py
```

Then open the URL that appears (usually `http://localhost:8501`).

---

## Project Structure

```
netflix-explorer/
├── app.py              # Main application (UI + visualizations)
├── movies.csv          # Dataset (1,040 titles)
├── requirements.txt    # Project dependencies
└── README.md           # This file
```

---

## About the Data

The dataset contains 18 columns per title, including: ID, title, content type, genre, release year, duration, rating, language, country of origin, IMDb rating, production budget, box-office revenue, number of seasons/episodes, and Netflix-original status.

---

## Author

**Ghadi**
[GitHub](https://github.com/Ghadi-cpu)

---

<div align="center">

### Built as part of a Data Analysis project

</div>
