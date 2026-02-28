# Data Pipeline Project

## 📌 Project Overview
This project implements a robust **Exploratory Data Analysis (EDA)** and **Data Pipeline** to process flight delay datasets. It handles data cleaning, log-transformation for handling skewed distributions, and generates high-level visualizations to identify key operational bottlenecks in the aviation industry.

---

## 🚀 Key Features

- **Data Ingestion:** Automated loading of flight datasets for analysis.  
- **Log Transformation:** Normalizes highly skewed data (e.g., delays up to 400,000 minutes) to visualize "typical" experiences.  
- **Exploratory Data Analysis:** Includes comparative boxplots, seasonal line plots, and correlation heatmaps.  
- **Root Cause Analysis:** Quantitative breakdown of Carrier, Weather, NAS, and Late Aircraft delays.  

---

## 📊 Data Insights

From our analysis:  

- **Major Bottlenecks:** Carrier and Late Aircraft issues account for nearly **74% of total delay minutes**.  
- **Seasonal Trends:** Delays peak significantly during **Summer (June–July)** and **December**.  
- **The Weather Myth:** While severe individually, weather accounts for only ~**6% of cumulative annual delay minutes**.  

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook / Google Colab  

---
