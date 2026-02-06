# Unemployment Analysis in India using Python
End-to-end data analysis project exploring unemployment trends in India using Python, visualization, and basic forecasting models.

## Overview
This project analyzes unemployment trends in India using real-world datasets. The notebook performs **data cleaning, exploratory data analysis (EDA), region-wise and area-wise comparisons, COVID-19 impact analysis, and basic machine learning–based forecasting**.

---

## Objectives
- Analyze unemployment trends over time in India  
- Study the impact of COVID-19 on unemployment rates  
- Compare unemployment across regions and areas (Urban vs Rural)  
- Examine labour participation patterns  
- Perform basic machine learning–based unemployment forecasting  

---

## Datasets Used
Two datasets are used in this project:

1. **Unemployment in India**
   - Date
   - Region
   - Area (Urban / Rural)
   - Estimated Unemployment Rate (%)
   - Estimated Employed
   - Estimated Labour Participation Rate (%)

2. **Unemployment Rate up to November 2020**
   - Date
   - Region
   - Estimated Unemployment Rate (%)
   - Estimated Employed
   - Estimated Labour Participation Rate (%)

Both datasets are loaded in CSV format and processed using Pandas.

---

## Tools & Technologies
- **Language:** Python  
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Environment:** Jupyter Notebook

---

## Project Workflow

### 1. Data Loading & Inspection
- Loaded both datasets using Pandas
- Checked dataset structure, data types, and summary statistics
- Inspected missing values and column consistency

---

### 2. Data Cleaning & Preprocessing
- Removed extra spaces from column names
- Converted `Date` columns into datetime format
- Prepared data for time-series analysis
- Encoded categorical region data for machine learning models

---

### 3. Exploratory Data Analysis (EDA)

#### Unemployment Trend Over Time
- Visualized national unemployment trends using line plots

#### COVID-19 Impact Analysis
- Filtered 2020 data
- Analyzed unemployment spikes during the COVID-19 period

#### Region-Wise Unemployment Analysis
- Compared average unemployment rates across regions using bar plots

#### Urban vs Rural Comparison
- Used box plots to compare unemployment rates between urban and rural areas

#### Labour Participation Rate Analysis
- Visualized labour participation differences by area

#### Correlation Analysis
- Generated a heatmap to study relationships between numerical variables

---

### 4. Machine Learning–Based Forecasting
- Converted dates to ordinal values for regression modeling
- Applied **Linear Regression** for:
  - Dataset 1: Date vs Unemployment Rate
  - Dataset 2: Date + Region (encoded) vs Unemployment Rate
- Evaluated models using **Mean Absolute Error (MAE)**
- Predicted unemployment rates for future months
- Visualized historical vs predicted unemployment trends

> Note: The ML models are used for **basic trend forecasting** and learning purposes.

---

## Key Insights
- Unemployment rates show clear temporal variation
- Significant increase in unemployment observed during COVID-19 (2020)
- Noticeable differences exist between regions and between urban and rural areas
- Labour participation rates vary significantly by area
- Simple regression models can capture short-term unemployment trends

