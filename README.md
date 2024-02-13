# Road Accident Dashboard

## Project Description
A major issue that has an impact on communities all across the world is road safety. In this project I have created a Road Accident Analytics Dashboard, a powerful tool designed to analyse and visualize road accident data for the years 2021 and 2022. This Excel-based dashboard empowers stakeholders with valuable insights to make data-driven decisions and pave the way towards safer roads.


## What I learnt and applied
- Data Cleaning, Data Transformation, Data Analysis
- Filtering, Sorting and Conditional function.
- Pivot Tables and Pivot Chart
- Data Visulisation and Dashboard creation

## Requirements and KPIs
Clients want to create a road accident dashboard for the years 2021 and 2022 so that they can have insight on following aspects-
- Primary KPI - Total Casualties and Total Accident values for Current Year and YoY growth
- Primary KPI's-Total Casualties by Accident Severity for Current Year and YoY growth
- Secondary KPIs - Total Casualties concerning vehicle type for the Current Year
- Monthly trend showing a comparison of casualties for the Current Year and the Previous Year
- Casualties by Road Type for the Current Year
- Current Year Casualties by Area/ Location & by Day/Night
- Total Casualties and Total Accidents by Location

## Data Sourcing
The dataset can be found [here](https://drive.google.com/file/d/1R_uaoZL18nRbqC_MULVne90h3SdRbAyn/view) .

## Data Cleaning and Transformation
This stage began with getting to know the dataset and checking for any data quality issues.
1.	Checking NULL values, blanks and Errors 
2.	Removing duplicates, and irrelevant columns.
3.	Made sure data is consistent and clean with respect to data type, data format and values used.
4.	Creating 2 new attributes 'Year' and 'Month' were added for logical and easy interpretation of dataset.

## Data Analysis

Created a "Data Analysis" sheet to summarize all the pivot table Data for a new user or developer or client to ease their work and gathered information. On this sheet nine pivot tables were created to summarise the data and help identify trends in the dataset focusing on relationship between number of casualties and many factors such as- casualty type, vehicle type, road type, location etc. Monthly trends were also analysed for the years 2021 and 2022.
Below is a snippet of the Data Analysis Sheet

![Data Analysis](https://github.com/kunal9960/Road_Accident_Data_Analysis/blob/main/Data%20Analysis.png)

## Data Visualization
Finally, the dashboard was created by inserting and customizing the pivot charts of corresponding pivot table. For user friendly and interactive experience slicers and timelines were incorporated. Hyperlinks and connections were also added to necessary icons for seamless navigation.
Below is a snippet of the final dashboard in Excel.

![Road Accident Dashboard](https://github.com/kunal9960/Road_Accident_Data_Analysis/blob/main/Dashboard.png)


## Key Insights 
📈 Total Casualties Analysis: The dashboard reveals that a staggering 417,883 casualties occurred after accidents during the two-year period

📅 Peak Months: Overall the number of casulaties were slightly higher in 2021 than 2022. Maximum Casualties happened in the month of October and November in both the Years and minimum casualties take place in  the month of January and February.

🚗 Casualties by Vehicle Type: Car accidents accounted for the highest number of casualties, contributing to 79.8% of the total. On the other hand, casualties were minimal in accidents involving other vehicle types.

🩸 Casualties by accident severity Slight severity form the bulk of casualties 84.1% whereas there are only 1.7% Fatal severity casualties.

🛣️ Road Type Analysis: Maximum Casualties by Single Carriageway road type (310.1K) and Minimum by Slip road(5.1K)

🌧️ Casualties Distribution by Road Surface: Highest Distribution of total casualties on Dry road surfaces (67%)

🏙️ Casualties Relation by Area/Location Urban areas form the majority of casualties after an accident (61%)

☀️ Casualties Distribution by light condtion: 73% of casulties take place in daylight condtion
