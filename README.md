# Los Angeles Crime Data Analysis

## Project Overview

This project explores crime data from Los Angeles, California, to identify patterns in criminal activity. Using Python and data analysis techniques, the goal is to uncover insights into when crimes occur, which areas experience the most nighttime crime reports, and the age distribution of crime victims.

The analysis is intended to support a better understanding of crime patterns and how data can inform resource allocation.

## Objectives

- Identify the hour of the day with the highest number of reported crimes.
- Determine which geographic area has the most reported crimes during nighttime hours.
- Group victims into age ranges for further analysis.
- Practice data cleaning, transformation, and exploratory data analysis using Python.

## Tools and Technologies

- **Python** — data analysis and manipulation
- **pandas** — data cleaning, transformation, and aggregation
- **NumPy** — numerical computing
- **Matplotlib** — data visualization
- **Seaborn** — statistical data visualization

## Dataset

The project uses `crimes.csv`, a modified version of crime data originally available through Los Angeles Open Data.

The dataset includes information such as:

- Crime report and occurrence dates
- Time of occurrence
- Geographic area or patrol division
- Crime description
- Victim age, sex, and descent
- Weapon description, where applicable
- Crime status and location

## Analysis and Methodology

### 1. Data Preparation
Loaded the dataset using pandas and preserved the crime occurrence time as a string to facilitate time-based analysis.

### 2. Peak Crime Hour
Extracted the hour portion of the reported occurrence time and identified the most frequently occurring hour.

### 3. Nighttime Crime Analysis
Filtered records for nighttime hours, defined in this notebook as 10:00 PM through 3:59 AM, and identified the geographic area with the highest number of records in that period.

### 4. Victim Age Groups
Grouped victim ages into categories ranging from 0–17 through 65 and older to prepare for age-based analysis.

### 5. Victim Age Distribution

Created a bar chart to visualize the distribution of crime victims across age groups. This visualization makes it easier to compare the frequency of reported victim records across different age categories and identify which groups are most represented in the dataset.

## Key Findings

- **Peak crime hour:** 12:00 PM (noon) was the most frequently represented hour in the dataset.
- **Nighttime crime location:** Central was the geographic area with the highest number of records during the defined nighttime period.
- **Victim demographics:** The analysis includes grouping victims by age to support further demographic exploration.

## Skills Demonstrated

- Loading and inspecting datasets
- String manipulation and time extraction
- Filtering and selecting records
- Frequency analysis and identifying modes
- Grouping numerical data into categorical age ranges
- Using pandas for exploratory data analysis

## Limitations

This analysis identifies patterns in the provided dataset. The results represent recorded crime reports and should not be interpreted as a complete measure of actual criminal activity or as proof that one area is inherently more dangerous than another.

## Conclusion

This project demonstrates how Python can be used to explore crime data, identify temporal patterns, and compare geographic areas. These techniques provide a foundation for more advanced exploratory analysis and data-driven decision-making.

