# 🌦️ Weather Data Analysis Report

## 📌 Objective
The goal of this project is to analyze weather data to identify patterns, trends, and insights using data visualization techniques.

---

## 📂 Dataset Information
The dataset contains the following columns:

- Date/Time
- Temp_C (Temperature)
- Dew Point Temp_C
- Rel Hum_% (Humidity)
- Wind Speed_km/h
- Visibility_km
- Press_kPa
- Weather

---

## 🧹 Data Cleaning
- Converted 'Date/Time' to datetime format
- Removed missing/null values
- Extracted Month from date for trend analysis

---

## 📊 Data Analysis & Visualizations

### 1️⃣ Temperature Trend (Line Chart)
- Monthly average temperature was calculated

📌 Insight:
- Temperature shows a clear seasonal pattern
- Mid-year months have higher temperatures
- Early and late months are cooler

---

### 2️⃣ Weather Distribution (Pie Chart)
- Top 5 most frequent weather conditions analyzed

📌 Insight:
- "Clear" and "Cloudy" weather dominate
- Extreme conditions (storm, snow) are less frequent
- Indicates mostly stable weather patterns

---

### 3️⃣ Wind Speed Analysis (Bar Chart)
- Average wind speed calculated for each weather condition

📌 Insight:
- Wind speed is higher during rainy/stormy weather
- Clear weather has relatively lower wind speed
- Strong winds are associated with unstable weather

---

## 📈 Key Findings

- Weather patterns follow seasonal trends
- Most days have stable weather conditions
- Wind speed increases during bad weather conditions
- Temperature and weather type are strongly related

---

## 📌 Conclusion

This analysis provides useful insights into weather behavior:
- Helps in understanding climate trends
- Useful for forecasting and planning
- Demonstrates how data visualization simplifies complex data

---

## 🚀 Future Improvements

- Add more years of data for deeper analysis
- Build an interactive dashboard (Power BI / Streamlit)
- Perform correlation analysis between variables