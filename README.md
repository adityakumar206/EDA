Crime Data Analysis Project

Overview
This project focuses on analyzing crime data from 2020 to the present for the city of Los Angeles. It involves data cleaning, exploratory data analysis (EDA), visualization, and predictive modeling to derive meaningful insights and trends.


Project Objectives
1.	Analyze overall crime trends from 2020 to the present.
2.	Identify seasonal patterns in crime data.
3.	Determine the most common crime types and their trends over time.
4.	Investigate regional differences in crime rates.
5.	Explore relationships between socioeconomic indicators like CPI and crime rates.
6.	Predict future crime trends using time series analysis.


Dataset Description
•	Source: Publicly available "Crime Data from 2020 to Present" for Los Angeles.
•	Attributes: Includes details such as date/time of occurrence, crime type, location, victim details, and weapon usage.
•	Size: 28 columns with thousands of records.


Tools and Libraries
•	Data Manipulation: Pandas, NumPy
•	Visualization: Matplotlib, Seaborn
•	Modeling: ARIMA (for time series forecasting)
•	Statistical Analysis: Chi-Square Test


Key Steps
1. Data Cleaning
•	Handled null values by using mean/median/mode.
•	Removed duplicates and outliers.
•	Corrected data types for date and numeric columns.
•	Encoded categorical columns for further analysis.

2. Exploratory Data Analysis (EDA)
•	Crime trends over time.
•	Seasonal and monthly patterns.
•	Most frequent crime types.
•	Regional differences in crime rates.

4. Advanced Analysis
•	Relationship between CPI and crime rates (weak negative correlation).
•	Chi-Square tests to explore hypotheses:
•	Differences in crime rates between weekdays and weekends.
•	Impact of victim age on crime type.

5. Predictive Modeling
•	Used ARIMA to forecast future crime trends.
•	Observed a general decline in crime after mid-2023.


Findings
•	Crime Trends: Highest in 2022; slight decline in 2023 and 2024.
•	Seasonality: Higher crimes in winter and early spring; lowest in November-December.
•	Regional Analysis: Central LA has the highest crime rate.
•	Top Crime Types: Battery - Simple Assault, Burglary from Vehicle, Theft of Identity.
•	Hypothesis Testing: Significant differences in crime rates by day of the week and victim age.


Insights
1.	Crime patterns can be influenced by socioeconomic factors and seasonal changes.
2.	High-crime areas and most frequent crime types can guide targeted interventions.
3.	Predictive modeling helps in resource allocation and crime prevention strategies.

