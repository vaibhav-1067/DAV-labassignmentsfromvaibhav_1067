# Data Analytics Lab Assignments

# Assignment 1 – Data Cleaning
This assignment performs data profiling, duplicate detection and removal, missing value analysis, placeholder value handling, data imputation, and final data validation using the earthquake dataset.

# Assignment 2 – Data Visualization
This assignment creates different visualizations from the cleaned earthquake dataset, including bar charts, histograms, box plots, violin plots, pie charts, scatter plots, line charts, and heatmaps. It also demonstrates honest and misleading visualizations.

#Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

  
# ** Assignment 3 – Data Exploration and Data Quality Assessment**
# Lab Assignment 3 – Data Exploration and Data Quality Assessment

## 📌 Overview

This lab assignment focuses on exploring and assessing the quality of an earthquake dataset using Microsoft Excel.

The dataset contains information about **1,000 significant earthquakes** recorded between 1995 and 2023, with **19 attributes** including magnitude, date and time, depth, alert level, location, magnitude type, latitude, longitude, continent, and country.

## 🎯 Objectives

- Explore the earthquake dataset using Excel formulas.
- Calculate basic statistical measures such as minimum, maximum, and average.
- Analyze earthquake counts by magnitude type and alert level.
- Create PivotTables and charts to identify patterns in the data.
- Identify missing values and calculate missing-value percentages.
- Audit and classify the data types of all dataset columns.
- Verify and convert date-time values into proper Excel datetime format.
- Identify different earthquake title formats.
- Normalize magnitude-type values using `LOWER()`.
- Detect duplicate earthquake events using title and date-time.
- Summarize data-quality issues and suggest fixes for future data cleaning.

## 🛠️ Tools Used

- Microsoft Excel
- Excel Formulas
- PivotTables
- Excel Charts

## 📊 Dataset

**Dataset:** `earthquake_1995-2023.csv`

The original dataset contains:

- **1,000 records**
- **19 columns**

### Main Attributes

`title`, `magnitude`, `date_time`, `cdi`, `mmi`, `alert`, `tsunami`, `sig`, `net`, `nst`, `dmin`, `gap`, `magType`, `depth`, `latitude`, `longitude`, `location`, `continent`, `country`

## 📋 Assignment Tasks

### Task 1 – Excel-Based Exploration

The dataset is explored using:

- `COUNTA`
- `COUNTBLANK`
- `COUNTIF`
- `ISNUMBER`
- `MIN`
- `MAX`
- `AVERAGE`

The analysis includes:

- Number of earthquake records
- Magnitude statistics
- Depth statistics
- Counts by magnitude type
- Counts by alert level
- PivotTable analysis
- Excel charts for visualizing patterns

### Task 2 – Data Type and Quality Audit

The dataset is audited for:

- Data types of all 19 columns
- Missing values
- Blank alert values
- Date-time formatting
- Title-format consistency
- Magnitude-type casing
- Duplicate earthquake events

A final data-quality summary is also prepared with recommended fixes for the next data-cleaning stage.

## 📁 Workbook Contents

The Excel workbook contains the original dataset, exploration results, data-quality analysis, PivotTables, charts, and final summary.

## 📌 Outcome

This assignment provides practical experience in **data exploration, data quality assessment, Excel-based analysis, and data visualization**, preparing the dataset for further cleaning and analysis in subsequent lab assignments.
