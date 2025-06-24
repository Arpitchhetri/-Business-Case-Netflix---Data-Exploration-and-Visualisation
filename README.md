# -Business-Case-Netflix---Data-Exploration-and-Visualisation

# 🎬 Netflix Data Analysis: Content Strategy & Growth Insights

This project presents an exploratory data analysis (EDA) of Netflix’s content catalog to help guide business decisions on content production and international expansion. The goal is to uncover patterns in movies/TV shows, understand user preferences by country, and offer data-driven recommendations to grow Netflix’s reach globally.

---

## 📁 Dataset Overview

The dataset includes metadata for all TV shows and movies available on Netflix, with the following columns:

- `show_id`: Unique ID of the title
- `type`: Movie or TV Show
- `title`: Title of the content
- `director`: Director(s) of the content
- `cast`: Main actors
- `country`: Country of production
- `date_added`: When the content was added to Netflix
- `release_year`: Year of original release
- `rating`: Audience rating (e.g., PG, TV-MA)
- `duration`: Duration in minutes (Movies) or number of seasons (TV Shows)
- `listed_in`: Genre(s)
- `description`: Content summary

---

## 🔍 Analysis Goals

- Understand content trends: What kind of content is produced most often? How has it evolved over time?
- Compare movies vs. TV shows: Has Netflix shifted focus?
- Analyze country-wise content availability: Which countries have diverse catalogs?
- Study content popularity by rating, genre, and duration
- Identify influential actors/directors frequently featured
- Suggest optimal time to release new shows based on historical data

---

## 🧰 Data Exploration Steps

1. **Initial Observations**
   - Dataset shape, missing values, data types
   - Categorical conversion & basic summary stats

2. **Non-Graphical Analysis**
   - Value counts and unique entries
   - Missing value checks and basic distributions

3. **Visual Analysis**
   - Univariate: Count plots, histograms, distplots (e.g., by type, year, genre)
   - Bivariate: Boxplots, groupby-based comparisons
   - Time-series: Release trends over the years
   - Multi-country content availability (via unnested `country` field)

4. **Outlier Detection**
   - Duration-based outliers
   - Rating or year-based inconsistencies

---

## 📊 Tools & Libraries Used

- Python (pandas, numpy)
- Matplotlib & Seaborn for visualizations
- Jupyter Notebook for data exploration
- PDF export for submission

---

## 🧠 Key Insights

- Movies dominate the platform but the share of TV shows has increased post-2015.
- Afternoon and year-end releases are more frequent, suggesting optimal launch periods.
- US, India, and UK produce the bulk of Netflix content. Many countries have limited local content.
- Most content is targeted at adult audiences (TV-MA, R), with limited family content.
- A small number of directors and actors appear repeatedly—signaling Netflix’s partnerships or preferences.

---

## ✅ Recommendations

- **Content Strategy:** Produce more TV shows, especially localized content in underrepresented countries.
- **Genre Focus:** Increase variety in genres like documentaries and family-friendly content.
- **Global Growth:** Encourage partnerships with local creators in emerging markets (e.g., Brazil, South Korea, Turkey).
- **Scheduling:** Focus releases in Q4 and late afternoons for maximum reach.
- **Talent Pool:** Invest in diverse talent rather than repeatedly using the same small pool of directors/actors.

---

## 📌 Outcome

This case study guides Netflix on what kind of content to produce, which countries to expand into, and how to optimize launch timings—all based on real data and observable trends.
