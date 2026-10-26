# 🌍 Global Earthquake Data Analysis

## 📌 Project Overview

This project explores global earthquake data using Python to understand earthquake magnitude, depth, geographic distribution, temporal patterns, and tsunami-related events.

The analysis includes data quality checks, data cleaning, exploratory data analysis (EDA), interactive visualizations, and correlation analysis.

## 🎯 Project Objectives

- Analyze earthquake magnitude and depth distributions.
- Identify locations with the highest recorded numbers of earthquakes in the dataset.
- Explore earthquake activity over time.
- Visualize earthquake locations and geographic density.
- Investigate the relationship between earthquake characteristics.
- Explore tsunami-related events and earthquake depth categories.
- Examine the approximate geographic distribution of earthquakes across major tectonic belts.

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** — data manipulation and analysis
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualizations
- **Plotly Express** — interactive charts and geographic maps
- **Google Colab** — notebook development and execution

## 📊 Project Workflow

### 1. Data Loading & Overview
- Load the earthquake dataset into a Pandas DataFrame.
- Inspect the dataset's shape, columns, data types, and sample records.

### 2. Data Quality Assessment
- Check missing values and data types.
- Identify duplicate records.
- Investigate potential hidden zeros in selected columns.
- Validate date formats and logical ranges.
- Compare earthquake magnitude values with information extracted from titles, where available.

### 3. Data Cleaning & Feature Engineering
- Standardize column names and clean text values.
- Convert date-time values and extract year, month, hour, and date features.
- Remove duplicate records.
- Investigate values that may represent missing measurements.
- Create earthquake magnitude and depth categories.

### 4. Exploratory Data Analysis (EDA)
- Explore earthquake activity over time.
- Compare earthquake counts across geographic locations.
- Analyze magnitude and depth distributions.
- Examine earthquake depth and magnitude categories.

### 5. Geographic Analysis
- Create interactive maps of earthquake locations.
- Explore geographic earthquake density.
- Categorize earthquake locations into approximate tectonic belt groups.

### 6. Correlation Analysis
- Investigate relationships between selected numerical earthquake features using correlation analysis.

### 7. Significant Earthquakes
- Identify and visualize the strongest earthquakes recorded in the dataset.
- Explore their magnitude, depth, and geographic locations.

### 8. Key Findings
- Summarize important patterns observed during the analysis.
- Explore tsunami-related records and temporal trends.

## 📈 Visualizations

The notebook includes:
- Magnitude and depth distribution charts
- Earthquake counts by category and location
- Temporal activity charts
- Interactive geographic scatter maps
- Geographic density visualizations
- Correlation heatmaps
- Top 10 strongest earthquake visualizations

## ⚠️ Limitations

- The dataset may focus on significant earthquakes rather than every earthquake worldwide; therefore, its counts may not represent total global seismic activity.
- Tectonic belt classification is approximate and based on geographic country-level grouping.
- Missing measurements and zero values must be interpreted according to the meaning of each variable.
- Correlation indicates association, not causation.
- Findings depend on the dataset's coverage, time range, and data quality.

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Upload the earthquake dataset when prompted.
3. Run the notebook cells in order.
4. Review the cleaning reports, analysis outputs, charts, and interactive maps.

## 👨‍💻 Author

**Ammar Mamdouh**

Computer Science Student | Data Analytics & Python

---

*This project demonstrates practical skills in data cleaning, exploratory data analysis, statistical analysis, and data visualization.*
