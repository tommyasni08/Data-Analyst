# [Data Analyst] Rides Data Analysis

Data Analysis Project
Analyze Rides data from Easy (E-Hailing) in Latin America from April - May 2018.

## Description

Raw data obtained from https://www.kaggle.com/datasets/easytaxi/week-18-rides-sample/data for the rides data

Pre-process data work done:

1. Remove all records for Eqypt and Qatar Countries
2. Transform passenger_id and driver_id to user friendly format
3. Convert datetime columns from UTC to America/Sao_Paulo time
4. Calculate the pickup_duration from all completed rides completed
5. Join with country code data to get the country name (data obtained from internet)

Create data visualization using tableau [link](https://public.tableau.com/app/profile/tommy.asni/viz/LatinAmericaRidesDataAnalysis/PickupDurationandDriverPerformanceAnalysis)
Consist of 3 main dashboards:

- Home Page (Quick Intro, Percentage of completed and uncompleted rides, Map to navigate rides by Country)
- Uncompleted Rides Analysis (Further studies on Uncompleted Rides). Solving issue and finding opportunity like: How to increase the ride completion rate, identify the timing of insufficient driver, try to recover user loss from frequent uncompleted rides, etc.
- Pickup Duration and Driver Performance (Further studies on Completed Rides). Solving issue and finding opportunity like:
  Decrease the pickup duration time, opportunity to improve driver assignment algorithms, identify the timing of insufficient driver, Opportunity to improve driver performance, etc.
