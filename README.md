# Netflix Content Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix dataset using Python. It explores content distribution, trends over time, popular genres, countries, ratings, and directors.

## Dataset

- **File**: `netflix1.csv`
- **Total Titles**: Checked using `len(data)`
- **Columns**: Includes `type`, `title`, `director`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, etc.

## Data Cleaning & Preparation
- Converted `date_added` to datetime format
- Created new columns:
  - `year_added`
  - `month_added`
  - `genres` (split from `listed_in`)
  - `duration_num` (extracted numeric duration)
- Checked for missing values and duplicates

## Analysis & Visualizations

### 1. Content Type Distribution
- Bar chart showing count of **Movies** vs **TV Shows**

### 2. Content Ratings
- Bar chart displaying frequency of different content ratings

### 3. Content Addition Trends
- Yearly trend of content added (Line plot)
- Monthly content addition pattern (Bar chart)

### 4. Genres Analysis
- Top 10 most common genres on Netflix
- Trend of top 5 genres over the years

### 5. Country Analysis
- Top 10 countries with the most content
- Top 10 countries that added content in specific years (2018, 2019, 2020, 2021)

### 6. Directors
- Top 10 directors with the most titles

### 7. Content Growth Over Years
- Comparison of Movies vs TV Shows added each year (Stacked Bar)
- Duration statistics for Movies

### Key Insights Printed
- Total number of titles
- Year range of content added
- Peak year for content addition
- Most common genre
- Most common rating

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn

**Project Purpose**:  
Practice of data cleaning, feature engineering, visualization, and answering business questions related to Netflix content trends.

Made for learning and revision.
