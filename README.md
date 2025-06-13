# Hydrabad_AQI_Analysis

# 🌆 Public Transport Impact on City Pollution – Hyderabad (2015–2017)

This project explores how air quality in Hyderabad changed between 2015 and 2017, focusing on the influence of public transport and urban infrastructure. Using real environmental data, the goal is to analyze pollutant trends, identify key AQI contributors, and generate insights for public health and city planning.

---

## 📌 Problem Statement

Air pollution is a critical issue in Indian cities. Hyderabad, one of the fastest-growing urban centers, has seen metro and transport infrastructure improvements in recent years. This project investigates whether such changes have had any measurable impact on air quality, especially AQI.

---

## 🎯 Objectives & KPIs

- Analyze AQI trends from 2015 to 2017
- Identify major pollutants influencing AQI (PM2.5, NO2, SO2, etc.)
- Explore pollution variations by *area* and *time (year/month)*
- Assess any reduction in pollution post-2016
- Build an interactive dashboard to communicate findings

---

## 📊 Dataset

Dataset from [Kaggle - Air Pollution in Indian Cities](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india), filtered for Hyderabad.

- station.csv: Station details (ID, area, city, state)
- city_day.csv: Daily pollution measures and AQI
- station_day.csv: Pollution data by station and date

---

## 🛠 Tools Used

- *Power BI* for dashboard development and visual storytelling
- *Power Query* for data cleaning, transformation, and modeling
- *DAX* for calculated columns and measures
- *Excel* for preliminary filtering

---

## 🧹 Data Cleaning

- Removed rows with more than 9 null values
- Filled remaining nulls with column averages
- Engineered AQI and AQI Bucket from pollutant levels
- Created a Date table for flexible time-based filtering
- Established relationships for data modeling

---

## 📈 Key Visuals in Dashboard

- ✅ *KPI Cards*: Avg AQI, Max AQI, Avg PM2.5, Avg SO2, etc.
- 📆 *AQI Over Time*: Line chart (Date vs Avg AQI)
- 📉 *PM2.5 vs AQI*: Correlation scatter plot
- 🍩 *AQI Bucket Distribution*: Donut chart
- 🎛 *Filters/Slicers*: Year, Month, AQI Bucket, Area

---

## 🔍 Insights

- PM2.5 is the strongest AQI driver.
- Slight AQI improvement seen after 2016.
- High pollution concentrations found in specific areas.
- Seasonal trends indicate higher pollution in winter months.

---

## 💡 Recommendations

- Focus on reducing PM2.5 emissions through construction dust control and vehicle checks.
- Increase public transport adoption through subsidies and awareness.
- Use electric buses in high-pollution areas.
- Expand green zones around traffic-heavy regions.

---

## 🗂 Files

- Hyderabad_Air_Pollution_Report.docx: Final project report
- PowerBI_Dashboard.pbix: Dashboard file (optional to upload)
- README.md: Project overview

---

## 👤 Author

*Sai Abhilash* – Data Analyst | Passionate about clean data and cleaner air 🌱

---

## 📬 Contact

For questions or collaboration opportunities, feel free to reach out via GitHub or [LinkedIn](#).

---

> "Better insights lead to better air." – This project supports sustainable urban planning through data-driven decision-making.
