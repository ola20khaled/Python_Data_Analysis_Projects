# 🚀 Space Missions Data Analysis

An exploratory data analysis (EDA) project on global space mission launches, exploring mission success rates, costs, organizations, and country-level activity from the dawn of the space age to modern day.
This Project was a practising project from the Udemy course "100 Days of Code: The Complete Python Pro Bootcamp for 2023."

---

## 🔍 Overview

This project analyzes a dataset of space mission launches to uncover trends in mission success, spending patterns, launch frequency, and the key players in the space industry, visualized through interactive charts and maps.

---

## 📁 Dataset

**File:** `mission_launches.csv`  
Includes mission date, launch location, organization, rocket status, mission status, and cost (in millions USD).

---

## 🧹 Data Cleaning

- Parsed `Date` column to datetime and extracted `Year` and `Month`
- Cleaned `Price` column (removed commas, converted to numeric)
- Imputed missing prices with the median
- Dropped unnamed index columns
- Extracted `Country` from `Location` and standardized country names
- Converted country names to ISO Alpha-3 codes for map plotting

---

## 📊 Visualizations Used

- **Pie charts** — mission status, rocket status
- **Bar charts** — top organizations by success count
- **Count plots** — launches per year and per month by mission status
- **Sunburst charts** — hierarchical breakdowns by country, org, and status
- **Line charts** — cost over time, spending by organization
- **Histogram** — launch cost distribution
- **Choropleth map** — number of launches by country

---

## 🛠️ Tools & Libraries

`pandas` · `numpy` · `matplotlib` · `seaborn` · `plotly` · `pycountry`
