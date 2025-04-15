# GOOGLE-DATA-ANALYTICS
"This repository contains projects and case studies related to the Google Data Analytics Certification. It includes data cleaning, analysis, visualization, and insights using tools like SQL, R, and Tableau. The goal is to apply real-world data analytics techniques to solve business problems and derive actionable insights."
## GOOGLE DATA ANALYTICS
## How does a bike share navigates speedy success
### Table Of Contents
- Introduction


- Overview of Cyclistic Bike-Share

- Business Objective
- Data Cleaning & Preparation
- Data Loading and Inspection
 - Handling Missing Values
- Data Cleaning and Formatting
- Exploratory Data Analysis (EDA)
- User Behavior: Casual Riders vs. Annual Members


Bike Type Preferences

- Peak Usage Trends (Time & Day Analysis)
- Key Insights & Findings
- Differences in Usage Patterns
- Seasonal and Temporal Trends
- Bike Type Performance
- Recommendations
- Strategies to Convert Casual Riders to Members
- Marketing and Promotional Ideas
- Operational Improvements
- Conclusion
- Summary of Findings


## Project Overview: Bike-Share Company Growth Strategy
Client: Cyclistic – a Chicago-based bike-share program
Challenge: Convert casual riders into annual members to increase profitability.

Objective: Analyze how different types of customers use Cyclistic bikes and provide actionable insights to inform a marketing strategy focused on increasing annual memberships.

Tools Used:

Data Sources: Historical trip data from Divvy (Cyclistic’s database)

Technologies:
- Excel - Cleaning Data [Download Here](https://docs.google.com/spreadsheets/d/1uCTsHlZLm4L7-ueaSLwDg0ut3BP_V4mKDo2IMpaXrk4/template/preview?resourcekey=0-dQAUjAu2UUCsLEQQt20PDA#gid=1797029090)
- R - Data Cleaning , Manipulation , Analysis , Visualisations
- SQL - Data Analysis
- Tableau - Creating Visualisations and dashboards

### Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:

- Data loading and inspection.
- Standardizing Data
- Headers Naming Convention
- Handling missing values.
- Data cleaning and formatting.

### Exploratory Data Analysis (EDA)
EDA involved exploring the Cyclistic bike-share data to answer key questions, such as:

- What are the differences in riding patterns between casual riders and annual members?

- Which types of bikes are preferred by each group?

 - What times and days see the highest bike usage?

### Data Analysis
Including some code features I worked with.
```sql
-- Basic query to see all the data in a table
SELECT * FROM `divvy-data-456911.Divvy_Data.Jan_Data` ;
SELECT * FROM `divvy-data-456911.Divvy_Data.Feb_Data` ;
SELECT *
FROM `divvy-data-456911.Divvy_Data.Mar_Data`;
```

### Key Questions Addressed:

How do annual members and casual riders use Cyclistic bikes differently?

What trends can be identified in ride duration, time of use, and bike type?

What marketing strategies could effectively convert casual riders into members?

Findings Summary:

Casual riders mostly take longer rides, especially on weekends.

Members are more consistent, commuting during weekdays.

Docked bikes are used more by casual riders, while classic bikes are preferred by members.

Recommendations:

Target weekend casual riders with discounts or trials for memberships.

Promote benefits like cost savings, ease of commuting, and priority access.
Use data to launch personalized marketing campaigns (e.g., email, in-app notifications).
