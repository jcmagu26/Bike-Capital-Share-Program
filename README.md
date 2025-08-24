# 🚲 Analysis of the Capital Bike Share Program  

This project explores bike rental patterns in the **Capital Bike Share program** using R for statistical graphics and data visualization. The dataset combines **bike rental data (2011–2012)** with **weather and seasonal information**, allowing us to examine how time, weather, and rider type influence bike share usage.  

## 📊 Project Overview  
This analysis was completed as part of **SC326: Statistical Graphics and Principles of Data Visualization** at Colby College.  

We investigated:  
- Trends across time (yearly, monthly, weekly, daily patterns)  
- Weather impacts on bike rentals (clear, misty, rainy/snowy days)  
- Casual vs. registered riders (commuting vs. recreational use)  
- Correlations between rider counts and variables like temperature, wind speed, and total rides  

## 📂 Dataset  
- **Source**: UCI Machine Learning Repository – Bike Sharing Dataset  
  https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset  
- Contains both daily and hourly rental counts from 2011–2012.  
- Includes corresponding weather and seasonal data.  

## 📈 Key Findings  
- Bike usage increased from 2011 to 2012, with more summer activity than winter.  
- Registered riders peak during commuting hours (8am and 5pm), while casual riders peak on weekends and afternoons.  
- Weather strongly influences ridership: clear days have the most rentals, with sharp declines in rain or snow.  
- Temperature has a positive effect up to ~35°C, after which usage declines.  
- Weekly patterns show higher correlations at 7-day intervals.  

## 🛠️ Tools & Methods  
- **Language**: R  
- **Libraries**: ggplot2, dplyr, tidyverse, lubridate  
- **Methods**: time-series analysis, correlation plots, seasonal trends, categorical comparisons  

## 📷 Visualizations  
The repository includes plots showing:  
- Daily and seasonal ridership trends  
- Weather impact on rentals  
- Casual vs. registered ridership patterns  
- Autocorrelation across time  

## 👥 Contributors  
- Freeman Buernor  
- Ryan Levine  
- Jane Maguire  
- Margaret Veatch  
 
