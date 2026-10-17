# NYC-Yellow-Taxi-Data-Analysis
Description: Exploratory Data Analysis of 3.47 million NYC Yellow Taxi trips using Python, Pandas, NumPy, Matplotlib, and Seaborn.



#  NYC Yellow Taxi Trip Data Analysis

##  Project Overview

This project explores the January 2025 NYC Yellow Taxi trip dataset using Python to identify travel patterns, trip demand, passenger behavior, frequently used routes, and data-quality issues.

The analysis covers data cleaning, feature engineering, exploratory data analysis (EDA), statistical analysis, outlier detection, correlation analysis, and business insights.

##  Objectives

- Analyze hourly and daily taxi demand.
- Explore trip distance and duration distributions.
- Understand passenger-count patterns.
- Identify popular pickup and drop-off locations and routes.
- Analyze payment types, vendors, and rate codes.
- Investigate missing values, unusual observations, and statistical outliers.
- Present findings through meaningful visualizations.

##  Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

##  Key Findings

- **Trips analyzed:** 3,475,102 after cleaning.
- **Busiest pickup hour:** 6 PM, with 267,949 trips.
- **Busiest day:** Thursday, with 614,208 trips.
- **Median trip distance:** 1.67 miles.
- **Median trip duration:** 11.7 minutes.
- **One-passenger trips:** Approximately 79.13% of trips with available passenger information.
- **Short-distance trips:** Approximately 58.98% of all trips.
- **Most frequent route:** Location ID 237 → 236, with 24,839 trips.

##  Analysis Performed

1. Initial data exploration and quality assessment
2. Data cleaning and feature engineering
3. Statistical analysis using NumPy
4. Time-based demand analysis
5. Trip distance and duration analysis
6. Passenger analysis
7. Pickup, drop-off, and route analysis
8. Payment type and vendor analysis
9. Rate code and store-and-forward analysis
10. IQR-based outlier detection
11. Correlation analysis
12. Advanced demand and route analysis
13. Business insights and KPI summary

##  Visualizations

The project includes hourly and daily demand charts, trip distance and duration distributions, passenger analysis, location and route charts, demand and correlation heatmaps, scatter plots, and outlier analysis.

##  Data Quality & Limitations

The analysis identified missing values, zero-distance trips, zero-duration trips, unusually long trips, and extreme calculated speeds. Statistical outliers were investigated rather than automatically removed.

Pickup and drop-off values represent TLC Taxi Zone IDs, not neighborhood names. The analysis covers January 2025 only, so the findings may not represent other months or seasons.

Extreme observations can affect summary statistics and calculated speeds. Any conclusions about fare-related fields should be based on the actual columns available in the dataset and their data quality.

##  Project Files

- `NYC_Taxi_Data_Analysis_Pradeep_Cheruku.ipynb` — Complete analysis, code, visualizations, and findings.
- `NYC_Taxi_Data_Analysis_Report.pdf` — Project report, if included.

##  How to Run

1. Download or clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the required `yellow_tripdata_2025-01.parquet` dataset.
4. Update the dataset path in the loading cell if necessary.
5. Run the notebook cells from top to bottom.

##  Author

**Pradeep Cheruku**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

