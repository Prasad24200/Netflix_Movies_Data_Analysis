# 🎬 Netflix Movie Data Analysis

This project performs exploratory data analysis (EDA) on a Netflix dataset containing details about movies and TV shows. Using Python libraries like Pandas, Matplotlib, and Seaborn, the project uncovers patterns, trends, and insights into Netflix’s content offerings.

---

## 🧩 Problem Statement

Netflix hosts thousands of movies and TV shows from all over the world. With such a large amount of data, understanding what kind of content is available, which countries produce the most, and how Netflix has evolved over time can help guide content strategy.

**Objectives:**
- Identify trends in Netflix content by year.
- Compare TV Shows vs Movies.
- Analyze popular genres, directors, and countries.
- Visualize content release timelines.

---

## 📁 Dataset Details

- **Source:** [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Attributes Include:**
  - `show_id`, `type`, `title`, `director`, `cast`
  - `country`, `date_added`, `release_year`
  - `rating`, `duration`, `listed_in`, `description`

---

## 📊 Exploratory Data Analysis

Key analysis steps:
- Data cleaning and null value handling
- Date parsing and feature engineering
- Grouping and aggregating by type, country, year
- Frequency counts of genres, countries, and directors
- Time series analysis of content additions

---

## 📈 Visualizations

- Content additions per year 📅
- TV Shows vs Movies count 📽️
- Top 10 countries producing Netflix content 🌍
- Most common genres 📚
- Monthly addition heatmap 🔥
- Top 10 directors and actors 🎭

---

## 🛠️ Tools & Technologies

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## 🚀 How to Run

1. Clone the repository
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
