# London Bike Share — Tableau Dashboard Project

An end-to-end data analysis project exploring London bike-sharing ridership patterns across weather conditions, seasons, and time periods, built with Python and Tableau.

## Project Overview

**Objective:** analyze bike ridership patterns across London, focusing on how temperature, weather conditions, wind speed, and temporal factors (holidays, weekends, seasons) affect the number of riders.

**Key visualization:** rider counts broken down by specific time periods and weather conditions.

## Data Source

- Downloaded from Kaggle (originally collected from a government site)
- 17,414 rows × 10 columns

## Workflow

1. **Data preparation (Python):** cleaning and validating the raw data in `tableau_project1-checkpoint.ipynb` to ensure accuracy and consistency.
2. **Visualization (Tableau):** building the dashboard around the main ridership drivers:
   - Temperature (t1 — actual, t2 — feels like)
   - Bike ridership count (cnt)
   - Weather conditions (weather_code)
   - Wind speed (wind_speed)
   - Temporal factors (holidays, weekends, seasons)

## Repository Contents

| File | Description |
| --- | --- |
| `London_bikes_cleaned_data.xlsx` | Cleaned dataset used in the Tableau dashboard |
| `london_merged uncleaned data.csv` | Raw, uncleaned source data |
| `tableau_project1-checkpoint.ipynb` | Python data-cleaning notebook |
| `Project Book Final.twbx` | Tableau workbook with the full dashboard |
| `TABLEAU PROJECT report .pdf` | Written project report |
| `TABLEAU PROJECT.pptx` | Project presentation slides |
