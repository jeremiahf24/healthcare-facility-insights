# Healthcare Facility Insights Platform 
This repository contains the code for a comprehensive healthcare facility insights platform developed using data obtained from the Community Benefit Insight. The platform provides real-time information about healthcare facilities, aiding stakeholders in strategic decision-making and resource allocation.

## Contributors 
Claire Bentzen, Jeremiah Fa’Atiliga, and Samantha Rivas

## Overview
The repository consists of the following components:
- Python scripts for data extraction, transformation, and loading (ETL)
- SQL scripts for data transformation and loading into a MySQL database
- Power BI visualization files for dashboard creation

## Deployment Process
1. Clone this repository to your local machine:
   git clone https://github.com/clairebentzen/healthcare-facility-insights.git

2. Set up a MySQL database, preferably on Azure, and connect it using the pymysql package in Python.
   
3. Run the main pipeline script to execute the ETL process and load the data into the database.

## Technologies Used 
- Python via Jupyter Notebook
- MySQL
- Azure
- Visual Studio
- Git
- Power BI
- Folium 

## Methods Used 
- EDA
- Data transformation
- Data Pipeline
- Data visulaization (Power BI and Folium)

## Monitoring Pipeline
1. Periodically re-evaluate the source data for changes.
2. Ensure records are loading into the tables correctly by referencing try/except rollback errors.
3. Implement a logging system.

## Refrences
Community Benefit Insight Hospital Data API (http://www.communitybenefitinsight.org/api/get_hospitals.php)
Bing Maps API
