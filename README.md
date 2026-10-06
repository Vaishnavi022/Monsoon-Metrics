# 🌧️ Monsoon Metrics

## India Rainfall Intelligence Dashboard

**Rainfall Patterns & State-Level Analysis | 2009–2024**

Monsoon Metrics is a data analytics project that analyzes rainfall patterns across India using historical daily rainfall data from **2009 to 2024**.

The project combines **Python, Pandas, MySQL, SQL, and Power BI** to explore rainfall seasonality, yearly variation, state-level differences, rainfall deviation, and Maharashtra-specific rainfall patterns.

---

## 📌 Project Overview

Rainfall varies significantly across different months, years, and states in India.

The objective of this project is to transform historical rainfall records into meaningful analytical insights through:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- SQL-based analysis using MySQL
- Interactive Power BI visualization
- State-level and seasonal analysis
- Rainfall deviation analysis

The final output is an interactive **Power BI dashboard** that provides a visual overview of rainfall patterns.

---

## 🎯 Objectives

The main objectives of Monsoon Metrics are:

- Analyze rainfall patterns across different years
- Understand monthly rainfall seasonality
- Compare Monsoon and Non-Monsoon rainfall
- Identify states with higher recorded rainfall
- Analyze year-to-year rainfall variation
- Study rainfall deviation from normal values
- Perform a focused analysis of Maharashtra
- Build an interactive dashboard for data exploration

---

## 🗂️ Dataset

**Dataset:** Daily Rainfall Data – India (2009–2024)

The dataset contains daily rainfall observations for Indian states and union territories.

### Dataset Information

- **Time period:** 2009–2024
- **Geographical coverage:** 36 states/union territories
- **Original records:** 204,876
- **Date range:** January 1, 2009 – July 31, 2024

### Main Columns

| Column | Description |
|---|---|
| `id` | Record identifier |
| `date` | Rainfall observation date |
| `state_code` | State/UT code |
| `state_name` | State/UT name |
| `actual` | Recorded rainfall |
| `rfs` | Rainfall-related reference value |
| `normal` | Normal rainfall value |
| `deviation` | Deviation from normal rainfall |

Additional analytical columns were created during preprocessing:

- `year`
- `month`
- `month_name`
- `quarter`
- `season`

### Season Classification

For this project:

- **Monsoon:** June, July, August, September
- **Non-Monsoon:** January–May and October–December

---

## 🛠️ Technologies Used

### Programming & Data Analysis
- Python
- Pandas
- NumPy
- Matplotlib

### Database & SQL
- MySQL
- MySQL Workbench
- SQL

### Data Visualization
- Microsoft Power BI
- Power Query

### Development Environment
- Jupyter Notebook
- GitHub

---

## 🔄 Project Workflow

```text
Rainfall Dataset
       ↓
Data Cleaning & Preprocessing
       ↓
Python Exploratory Data Analysis
       ↓
MySQL Database
       ↓
SQL Analysis
       ↓
Power BI Visualization
       ↓
Interactive Rainfall Dashboard
       ↓
Insights & Conclusions
