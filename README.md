# Unemployment Rate Analysis in India (2020) 📊

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-FF6F00?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge)

**Exploratory Data Analysis & COVID-19 Impact Study on Unemployment in India**

---

##  Project Overview

This project analyzes the **Unemployment Rate in India** up to November 2020 using the "Unemployment_Rate_upto_11_2020.csv" dataset. The main focus is to understand how the **COVID-19 pandemic** affected unemployment across different regions and time periods.

The analysis covers national trends, regional disparities, monthly patterns, and the drastic impact of lockdowns on India's labor market.

---

##  Objectives

- Clean and preprocess the unemployment dataset
- Explore national and regional unemployment trends
- Analyze the impact of COVID-19 on unemployment rate (Before vs After)
- Identify seasonal/monthly patterns
- Provide data-driven insights and policy recommendations

---

##  Technologies Used

- **Python**
- **Pandas** – Data cleaning and analysis
- **Matplotlib & Seaborn** – Data visualization
- **Datetime** – Time series handling

---

## 📁 Dataset

- **File**: `Unemployment_Rate_upto_11_2020.csv`
- **Time Period**: January 2020 – October 2020
- **Key Columns**:
  - `Region`
  - `Date`
  - `Estimated Unemployment Rate (%)`
  - `Estimated Employed`
  - `Estimated Labour Participation Rate (%)`
  - `longitude`, `latitude`

---

##  Data Cleaning & Preprocessing

- Stripped whitespace from column names
- Renamed columns for clarity
- Converted `Date` to datetime format
- Handled missing values by filling with column means
- Created new features: `Period` (Before/After COVID) and `Month`

---

##  Key Visualizations & Analysis

### 1. National Unemployment Trend Over Time
- Clear spike in unemployment during April–June 2020 due to nationwide lockdown.

### 2. Regional Unemployment Trends
- Line plot showing unemployment rate changes across all Indian states/regions.

### 3. Before vs After COVID-19 Impact
- Bar chart comparing average unemployment rate before and after March 2020.

### 4. Monthly Seasonal Pattern
- Average unemployment rate by month with highlight on above-average months.

### 5. Regional Comparison Table
- Detailed comparison of unemployment rates **Before** and **After** COVID-19 for all regions.

---

##  Key Insights

- **Sharp Spike**: Unemployment rate peaked dramatically in **April–June 2020** due to COVID-19 lockdowns.
- **Highest Impact Regions**: Puducherry, Tamil Nadu, Bihar, Jharkhand, and West Bengal showed massive increases after COVID.
- **Pre-existing Issues**: Tripura had the highest unemployment even before the pandemic.
- **Monthly Pattern**: April and May consistently show the highest unemployment rates.
- Some states like Chhattisgarh showed slight improvement after the initial shock.

---

## 🛠️ Policy Recommendations

- Implement emergency job protection programs during crisis periods (April–June).
- Design region-specific recovery plans for highly affected states.
- Promote skill development, digital upskilling, and MSME support.
- Build long-term structural reforms in states with chronically high unemployment.

---

## 📌 Conclusion

The COVID-19 pandemic caused a severe but temporary shock to India's labor market, with unemployment rising sharply during the lockdown period. However, the impact was highly uneven across regions. This analysis highlights the importance of **data-driven, region-specific policies** to build a more resilient workforce in India.


---

Feel free to explore the code and visualizations. Contributions and suggestions are welcome!
