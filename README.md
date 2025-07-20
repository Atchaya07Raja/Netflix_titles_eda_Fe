# Netflix_titles_eda_Fe

# 📺 Netflix Titles Analysis

This project performs exploratory data analysis (EDA), cleaning, and feature engineering on Netflix's publicly available content dataset. It reveals trends in content types, genres, country-wise distribution, and release patterns over time.


---

## 🎯 Project Objective

Analyze trends and patterns in Netflix’s global content library

Clean and transform raw data for visual storytelling

Identify high-performing genres, countries, and release periods

Engineer new features (month/year added) to derive deeper insights.


---

## ❓ Key Questions (KPIs)

What is the distribution of content by type (Movies vs TV Shows)?

Which countries contribute the most content to Netflix?

How has Netflix content grown over the years?

What are the top 10 most common genres?

How does content addition vary by month and year?

How are content ratings distributed by type?



---

## ⚙ Process

✅ Imported and cleaned dataset using Pandas & NumPy

✅ Handled null values and corrected data types for date fields

✅ Extracted year_added, month_added for trend analysis

✅ Used .explode() to analyze multiple genres per title

✅ Visualized patterns using Seaborn and Matplotlib

✅ Engineered insights using value counts, groupby, and sorting



---

## 📊 Visualizations

1. Distribution of Content Type

Movies dominate over TV Shows


2. Top 10 Countries by Content

U.S. leads, followed by India and the UK


3. Content Released Over the Years

Spike in content after 2015, peaking near 2019


4. Top 10 Genres

International Movies, Dramas, and Comedies are most common


5. Monthly Additions by Year

December and October are high-content months


6. Distribution of Ratings by Type

TV-MA and TV-14 are common for TV; PG and R for Movies



---

## 🔍 Insights

Over 4,000+ Movies vs ~2,000 TV Shows

United States and India contribute the highest number of titles

Content growth on Netflix surged after 2015, peaking around 2019

Dramas and Comedies remain the most popular genres globally

Netflix tends to release more content in Q4 (Oct–Dec) annually

TV content skews towards TV-14, while Movies have more PG/R ratings



---

## ✅ Conclusion

This analysis highlights how Netflix content has evolved globally. With the majority of content originating from the U.S. and India, and genre trends skewing toward dramas and comedies, this dataset reveals strategic content decisions. Feature engineering like date extraction and genre splitting enhances the dataset's depth, supporting more granular EDA.
