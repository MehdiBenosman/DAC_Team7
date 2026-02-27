# Data Analysis Challenge, Team 7, Weather and Air Quality

## Project Overview

In this project we analyzed a one-year dataset (365 days) containing daily weather and air quality data for multiple cities. The goal was to clean the data, perform statistical analysis, and answer six analytical questions related to temperature, air quality, seasonality, and precipitation.

---

## Project Files

- ‘DAC_Team7.ipynb': Notebook containing data cleaning, analysis, and visualizations.
- ‘team07_weather.csv': Dataset containing daily weather and air quality data for multiple cities.
- ‘README.md’: Project documentation explaining the analysis and how to run the project.
- ‘DAC_Team7_Video.mp4’: Recorded presentation demonstrating the notebook execution and key findings.

---

## Data Cleaning

The following steps were performed:

- Removed extra spaces from column names
- Converted ‘date’ to datetime format
- Converted ‘city’, ‘season’, ‘air_quality’ to string
- Converted ‘aqi’ from float to nullable integer (Int64)
- Handled missing values using:
  - Mean imputation
  - 7-day rolling average
- Checked for impossible values (e.g., negative precipitation, humidity above 100%)
- Detected outliers using the IQR method

After cleaning, the dataset contained no missing values and valid data ranges.

---

## Analysis Questions

1. Which city has the highest average temperature?
2. How does air quality vary by season?
3. What is the correlation between temperature and AQI?
4. Which month has the worst air quality on average?
5. How does precipitation affect air quality?
6. What percentage of days have 'Good' air quality in each city?

---

## Key Findings

- Temperature differs across cities.
- Air quality varies by season.
- Temperature and AQI show a very weak correlation.
- One month recorded the highest average AQI.
- Precipitation has a weak negative relationship with air quality.
- The percentage of 'Good' air quality days varies between cities.

---

## What we Used

- Python
- Pandas
- NumPy
- Matplotlib

---

## How to Run

1. Download the repository files.
2. Make sure the dataset file (‘team07_weather.csv’) is in the same directory as the notebook.
3. Open the notebook file (‘DAC_Team7.ipynb’).
4. Run all cells in order.

---

## Video Demo

A video presentation accompanies this project.

The video demonstrates:
- The data cleaning process
- The analysis steps with visualizations
- Final conclusions

During the presentation, the notebook is executed to explain the steps and the results.
