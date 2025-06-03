# Analyzing NYC 311 Service Requests  
### A Data-Driven Look at Public Complaints in New York City

## 📋 Project Overview

This project analyzes New York City’s 311 service request data to understand how residents interact with local government through complaint filings. Using publicly available records, the analysis explores trends in complaint types, borough-level distribution, and hourly reporting patterns. The goal is to uncover insights that can inform urban planning, resource allocation, and citizen engagement strategies.

---

## 🗂 Dataset

- **Source**: [NYC Open Data – 311 Service Requests](https://data.cityofnewyork.us/)
- **Size**: ~1M+ records (sampled subset for performance)
- **Key Fields**:
  - `Complaint Type`
  - `Created Date`
  - `Borough`
  - `Agency`
  - `Resolution Description`
  - `Hour` (extracted)

---

## 🎯 Objectives

- Identify the most common types of 311 complaints
- Explore how complaint volume varies by **borough** and **hour of day**
- Visualize spatial and temporal trends in NYC service requests
- Support urban analytics with clear, interpretable visualizations

---

## 📊 Key Visualizations

- **Bar Chart: Top 10 Complaint Types**
- **Line Plot: Complaint Volume by Hour of Day**
- **Bar Chart: Complaints by Borough**

---

## ✅ Sample Insights

- **Top Complaints** include Noise, Illegal Parking, and Blocked Driveways
- **Complaint volume peaks** between **3 PM and 6 PM**, with relatively fewer overnight
- **Brooklyn and the Bronx** receive the most 311 complaints overall
- Patterns suggest potential correlations with population density and urban infrastructure issues

---

## 🧰 Tools Used

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- NYC Open Data API

---

## 📁 Files

- `Project 3 - NYC 311 Calls.ipynb`: Full cleaned analysis notebook (EDA and visuals)
- `311_subset.csv` *(optional)*: Sampled/cleaned version of the dataset for reproducibility

---

## 🚀 Potential Extensions

- Cluster complaint types to identify systemic city service issues
- Join complaint data with NYC ZIP Code shapefiles for interactive geospatial analysis
- Add resolution times (if available) to evaluate city performance

---

## 📌 Note

This project uses public, de-identified data from NYC Open Data. All analyses are intended for educational and exploratory purposes.
