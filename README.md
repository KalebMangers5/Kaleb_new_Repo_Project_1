# Kaleb_new_Repo_Project_1
# Project 1 – Organizing and Summarizing Air Quality Data

## Client
UNMC Water, Climate, and Health Working Group

## Purpose
The purpose of this project is to analyze daily air quality data from PurpleAir sensors across Nebraska. The analysis identifies locations with elevated concentrations of VOC, PM2.5, and PM10 and highlights potential air quality hotspots that may be relevant to public health.

## Data Used
- `AirQuality_Daily_StudentVersion.csv`  
  Daily air quality data provided by the client. No modifications were made to the raw data.

## Analysis Overview
The analysis was completed using Python in a Jupyter Notebook and includes:
- Cleaning and organizing daily air quality data
- Grouping data by sensor location
- Calculating mean and median concentrations for VOC, PM2.5, and PM10
- Identifying the top five locations with the highest pollutant concentrations
- Identifying dates and locations of maximum pollution events
- Evaluating air quality patterns related to humidity, temperature, and sensor altitude
- Identifying potential AQI health risk events

## Repository Contents
- `AirQuality_Daily_StudentVersion.csv` – Raw data file used for analysis  
- `Project1_AirQuality_Analysis.ipynb` – Jupyter Notebook containing all analysis code  
- `README.md` – Project description and documentation  

## External Resources Used
The following resources were used for AQI standards, data context, and reference information:

- PurpleAir US EPA AQI standards map  
  https://map.purpleair.com/air-quality-standards-us-epa-aqi

- PurpleAir Community API documentation  
  https://community.purpleair.com/c/data/api/18

- AirNow (EPA air quality and AQI information)  
  https://www.airnow.gov/

- EPA Air Quality Index document (course-provided PDF)  
  https://uofnebraska-my.sharepoint.com/personal/37381171_nebraska_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2F37381171%5Fnebraska%5Fedu%2FDocuments%2FTeaching%2FCIVE%20202%2FSpring%202026%2FProject%20%231%2FEPA%20Air%20Quality%20Index%20Document%2Epdf

## Notes
All analysis results are grouped by sensor name as requested by the client. AQI thresholds and health categories were interpreted using EPA guidance and PurpleAir reference materials.
