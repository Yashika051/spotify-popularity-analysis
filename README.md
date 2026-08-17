# 🎧 Spotify Track Popularity Analysis

> Exploring 114,000 Spotify tracks to understand how genre, sound, and artist patterns relate to track popularity.

---

## 📌 Overview

What makes a Spotify track popular?

This project explores **114,000 tracks across 114 genres** to investigate whether popularity is associated with a track's genre, audio characteristics, or artist-level patterns.

Rather than trying to predict popularity with a machine learning model, the goal is to **understand the data and uncover meaningful patterns through exploratory analysis and analytical SQL**.

The project combines Python-based data analysis, SQL exploration, data visualization, and a visual Quarto report.

---

## 🎯 Questions Explored

The analysis focuses on four main questions:

1. **How popular are Spotify tracks overall?**
2. **Does genre influence average track popularity?**
3. **Do audio characteristics have a strong relationship with popularity?**
4. **Do some artists consistently have more popular tracks?**

---

## 📊 Key Findings

### 🎵 Popularity is concentrated toward the lower end

The average track popularity is **33.24**, with a median of **35**.

Around **34,177 tracks — nearly 30% of the dataset — have popularity between 0 and 20**, while only **954 tracks** fall into the 81–100 range.

Highly popular tracks therefore represent a relatively small portion of the Spotify catalogue represented in this dataset.

### 🎼 Genre matters

Average popularity varies substantially across genres.

Among the highest-ranked genres in this dataset are **pop-film, k-pop, chill, and sad**, while several niche genres occupy the lower end of the distribution.

This suggests that genre provides important context when comparing track popularity.

### 🎧 No single audio feature dominates

The analysis examined correlations between popularity and ten audio features across genres, including:

- Danceability
- Energy
- Loudness
- Speechiness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo
- Duration

Most relationships are relatively weak.

This suggests that **track popularity cannot be explained by one simple audio characteristic** and that the relationship between a track's sound and its popularity is more nuanced.

### 👤 Artist patterns matter too

Artist-level popularity varies considerably across the dataset.

To avoid comparisons based on artists with only a few tracks, the artist analysis focuses on artists with **at least 10 tracks**.

Among the strongest performers are **Måneskin and Lil Nas X**, although artist representation in the dataset is uneven and average popularity should therefore be interpreted carefully.

---

## 🛠️ Tech Stack

### 🐍 Data Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### 🗄️ SQL & Databases

![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### 📊 Visualization & Reporting

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![Quarto](https://img.shields.io/badge/Quarto-39729E?style=for-the-badge&logo=quarto&logoColor=white)

---

## 📁 Project Structure

The project is organized into separate areas for data, analysis notebooks, and the final report.

<!-- The exact notebook filename and additional report files will be added here later. -->

---

## 🔍 Analysis Workflow

The project follows a structured exploratory workflow:

**Raw Dataset → Data Exploration → Popularity Analysis → Genre Analysis → Audio Feature Correlations → Artist Analysis → SQL Exploration → Key Findings**

The emphasis is on **understanding patterns and communicating insights**, rather than treating correlation as causation.

---

## 📈 Analysis Report

The full analysis is presented as a **Quarto HTML report** designed as a visual data story.

The report includes:

- Dataset overview
- Popularity distribution
- Genre-level popularity comparison
- Audio feature correlations
- Artist-level popularity analysis
- Analytical SQL exploration
- Key findings and interpretation

<!--
### 🌐 Interactive Report

The Quarto report will be deployed using GitHub Pages.

🔗 [View the full analysis](YOUR_GITHUB_PAGES_LINK)
-->

---

## 🧮 SQL Analysis

The project uses **DuckDB** for analytical SQL exploration.

The SQL analysis examines the dataset from a database perspective and complements the Python-based exploratory analysis.

<!--
Specific SQL queries and results will be documented here once the SQL
files are added to the repository.
-->

---

## ⚠️ Limitations

Popularity is influenced by many factors that are not captured by audio features alone.

The dataset also contains uneven representation across genres and artists, meaning that averages for smaller groups should be interpreted carefully.

Most importantly, the correlations explored in this project describe **associations, not causal relationships**.

---

## 💡 What This Project Demonstrates

This project demonstrates an end-to-end analytical workflow involving:

- Data exploration
- Data aggregation
- Exploratory data analysis
- Statistical correlation analysis
- SQL-based analysis
- Data visualization
- Analytical storytelling
- Insight generation

The focus is not simply on producing charts, but on **asking questions, investigating patterns, and explaining what the data actually suggests**.

---

## 👩‍💻 Author

**Yashika Puri**

Data Analyst | Data Storyteller

> Exploring data, finding patterns, and turning analysis into decisions.

---

<!--
## 🚀 Future Improvements

- Add predictive modelling for track popularity
- Explore feature importance
- Compare different machine learning models
- Add an interactive dashboard
- Deploy the Quarto report using GitHub Pages
-->

⭐ If you found this analysis interesting, feel free to explore the repository and the full report.
