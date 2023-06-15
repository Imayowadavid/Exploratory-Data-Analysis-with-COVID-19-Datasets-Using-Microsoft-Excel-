**EXPLORATORY DATA ANALYSIS ON  GLOBAL COVID-19 CASES**.
![](covid19.jpg)
***
**INTRODUCTION**

This is my first  project. My sole aim is to carry out Exploratory Data Analysis on the Global COVID-19 (2020-2022) datasets. The 3 years (2020-2022) datasets were merged to form a consolidated Table. The Extraction, data cleaning and visualizations were done using Microsoft Excel. This Project file (https://drive.google.com/drive/folders/1ZtvsUQZr3YY51eBzf0Eq9HYy7tp8LlZ3) comprises the daily time series data, charts and summary of the analysis with pivot tables.
Datasets (Confirmed, Death, Recovered cases and Consolidated Table).

1. Overview
2. Datasets (Confirmed, Death, Recovered cases and Consolidated Table) details
3. Data Preparation
4. Data Visualization 
5. Summary of Analysis (Findings

***
 **Project Objective**
 ***
To analyze the COVID-19 victims( Top and Bottom 5 countries with the highest and lowest Confirmed, Deaths )from January 2020 to June 2022.
***
**Data Sourcing**
***

Data was scraped from the web into excel so as to have a real-time update.
Three time series tables representing the global confirmed cases, recovered cases and deaths were scraped from   CSSEGISandData/COVID19 on GitHub.
***
**Data Transformation**
***
Analysis was done using Power Query Editor.
- Unpivot was done on the date column
- The three time series tables were merged to form the consolidated table.
- Tables were named accordingly; Consolidated, Recovered, Death columns , Date columns were created using Text function for corresponding month, year and day. 
![](dashboardcovid19.jpg)
***
**DATA VISUALIZATION**
***
Dashboard                         
:-------------------------------:
![](coviddashboard.jpg) 

 Findings calculation
 :-------------------------------:
![](covidfindings.png)

Data visualization tab summarizes;
- Sum of confirmed and death cases
- Sum of confirmed cases by year 
- Top and Bottom 5 countries with sum of confirmed ,death cases,Death rate.


