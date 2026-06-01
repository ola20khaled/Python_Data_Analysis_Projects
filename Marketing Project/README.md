# 📊 Customer Marketing Data Analysis

An exploratory data analysis (EDA) project on a marketing dataset, uncovering customer demographics, spending behavior, and channel performance to support data-driven marketing decisions.

---

## 🔍 Overview

This project walks through the full EDA pipeline — from cleaning messy data to visualizing actionable insights — using Python in Google Colab.

---

## 📁 Dataset

**File:** `marketing_data.csv`  
The dataset includes customer demographics, purchase history across product categories and channels, campaign responses, and website activity.

---

## 🧹 Data Cleaning

- Imputed missing `Income` values with the median
- Removed duplicate records
- Dropped rows with invalid `Marital_Status` values (`'Absurd'`, `'YOLO'`)
- Removed customers born before 1940 (age inconsistency with purchase date)
- Removed a single extreme income outlier
- Converted `Dt_Customer` to datetime format

---

## 🛠️ Tools & Libraries

`pandas` · `numpy` · `matplotlib` · `seaborn` · `plotly`

