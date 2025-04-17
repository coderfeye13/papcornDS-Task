# 📊 Papcorns Data Science Technical Assessment

This repository contains a Jupyter Notebook developed for the Papcorns Data Scientist technical assessment. The notebook walks through the process of connecting to a SQLite database, performing exploratory data analysis (EDA), and extracting actionable insights from the user and event data.

## 📁 Project Structure

- `papcorns_analysis_template.ipynb` — Main notebook containing the complete workflow.
- `papcorns.sqlite` — SQLite database used as the data source (should be placed in the same directory).

## 🧰 Technologies Used

- Python 3
- Pandas
- SQLite3
- Matplotlib & Seaborn (for data visualization)
- Jupyter Notebook

## 🔍 Overview of Analysis Steps

1. **Environment Setup & Database Connection**
   - Connecting to the `papcorns.sqlite` database.
   - Listing available tables.
   - Loading and previewing data from the `users` and `user_events` tables.

2. **Exploratory Data Analysis (EDA)**
   - Data cleaning and preprocessing.
   - Univariate and bivariate analysis of user attributes and event interactions.
   - Visualization of key patterns and trends.

3. **Insight Extraction**
   - Identifying user behaviors and usage patterns.
   - Highlighting anomalies or noteworthy segments.
   - Summarizing findings for business relevance.

## 📌 Usage Instructions

1. Clone this repository.
2. Ensure that `papcorns.sqlite` is located in the root directory.
3. Open the notebook using Jupyter and run cells sequentially.

```bash
jupyter notebook papcorns_analysis_template.ipynb
