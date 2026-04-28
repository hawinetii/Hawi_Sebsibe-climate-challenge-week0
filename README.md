# 🌍 African Climate Trend Analysis – Week 0

## 📌 Project Overview
This project analyzes historical climate data from five African countries (Ethiopia, Kenya, Sudan, Tanzania, Nigeria) to support data-driven insights for COP32 climate negotiations.

The goal is to identify:
- Climate trends
- Seasonal patterns
- Cross-country differences
- Climate vulnerability levels

---

## 🎯 Objectives
- Understand climate variability across Africa
- Identify long-term temperature and rainfall trends
- Compare countries based on climate indicators
- Build a simple climate vulnerability ranking

---

## 📊 Dataset Description
NASA POWER dataset including:
- Temperature (T2M, T2M_MAX, T2M_MIN)
- Rainfall (PRECTOTCORR)
- Humidity (RH2M)
- Wind speed (WS2M)
- Pressure (PS)

Time range: 2015 – 2026

---

## 🧹 Data Processing Steps
- Converted YEAR + DOY into Date format
- Handled missing values (-999 → NaN)
- Removed duplicates
- Performed forward fill for continuity
- Extracted Month for seasonal analysis

---

## 📈 Key Analyses

### 1. Exploratory Data Analysis (EDA)
- Temperature trends
- Rainfall seasonality
- Humidity patterns
- Wind variability

### 2. Correlation Analysis
- Temperature vs Humidity (negative correlation)
- Rainfall vs Humidity (positive correlation)

### 3. Cross-Country Comparison
- Average temperature comparison
- Rainfall distribution
- Humidity differences

### 4. Climate Vulnerability Index
A simple risk scoring model combining:
- Temperature exposure
- Rainfall variability
- Humidity conditions

---

## 🌍 Key Insights

- Sudan & Nigeria show highest climate risk exposure
- Ethiopia & Kenya show moderate variability
- Tanzania shows relatively stable but changing patterns
- Rainfall patterns are becoming more irregular across all countries
- Temperature trends indicate gradual warming

---

## 🚀 Future Work
- Add machine learning forecasting models
- Integrate agricultural yield data
- Build interactive Streamlit dashboard
- Expand dataset to more African countries

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 👨‍💻 Author
Hawi Sebsibe Tadesse
Software Engineering Student
