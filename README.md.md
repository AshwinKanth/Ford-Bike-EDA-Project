
Ford GoBike System - Exploratory Data Analysis (EDA)

This project performs an Exploratory Data Analysis (EDA) on the Ford GoBike sharing system data for January 2018, using Python. The goal is to uncover usage patterns, user behaviour, and other insights from the bike-sharing system.



Project Objectives

• Clean and prepare real-world bike-sharing data
• Analyze ride duration, usage frequency, and peak hours
• Compare user behaviors (e.g., Subscribers vs Customers)
• Understand demographic usage (gender, trip times, etc.)
• Visualize key trends using clear and intuitive charts


Tools & Technologies

• Python (Google Colab)
• Pandas & NumPy – data handling
• Matplotlib & Seaborn – visualizations
• Plotly – optional interactive charts
• Colab – development environment



Dataset

File: ‘201801-fordgobike-tripdata.csv’
Source: [Ford GoBike System Data](https://www.fordgobike.com/system-data)
Rows with fields such as:
  - `start_time`, `end_time`, `start_station_name`, `bike_id`
  - `user_type` (Subscriber or Customer)
  - `member_gender`, `start_hour`, and `trip_duration_minutes` (engineered)


Key Features of the EDA

• Data Cleaning & Wrangling
• Converted time columns to datetime
• Created new features like trip_duration_minutes, start_hour, etc.
• Removed duplicates and invalid entries

Univariate Analysis

• Trip Count by User Type
• Gender Distribution
• Top 5 Start Stations

Bivariate Analysis

• Average Trip Duration by User Type
• Gender vs User Type
• Average Trip Duration by Gender
• Trip Count by Bike ID (Top 20 Bikes)


Multivariate Analysis
• Hourly Usage by User Type
• Trips by Start Station, Colored by User Type
• Trip Count by Start Hour and User Type



Insights Summary

• Male users account for most rides, trip durations are slightly longer for Other gender category.
• Customers have higher average trip duration compared to subscribers.
• Subscribers use bikes more compared to customers.
• A few bikes and stations experience significantly higher usage, possibly due to location.


Future Improvements

• Add maps to visualize trip flows between stations
• Include more months of data for seasonal trends
• Use clustering or time series models for predictive insights



License

Dataset is publicly available under the [Ford GoBike system data license](https://www.fordgobike.com/system-data).

