

This is the case study I colmpleted for my Google Data Analytics Professional Certificate.

# **Goal**
The goal of this project is to analyze the usage patterns of Cyclistic bikes among members and casual riders, with a focus on identifying key differences. Additionally, the project aims to explore strategies for converting casual riders into members.

# **Background**
Cyclistic is a bike-share program in Chicago offering a diverse fleet of over 5,800 bicycles, including traditional bikes, reclining bikes, hand tricycles, and cargo bikes. The company uses flexible pricing plans, such as single-ride passes, full-day passes, and annual memberships, to cater to different types of riders.

Annual members are more profitable than casual riders, who typically purchase single-ride or full-day passes. While casual riders already use Cyclistic bikes and are familiar with the service, the company sees an opportunity to convert them into long-term members.

# **Business Task**
The business task is to understand how casual riders and annual members use Cyclistic bikes differently. By analyzing the behavior and usage patterns of both groups, we can identify trends and insights that will inform strategies aimed at converting casual riders into annual members. These insights will provide the necessary foundation for a targeted marketing strategy to increase membership, which is key to Cyclistic’s growth and profitability.

# **Data Source**
For this analysis, we will use Cyclistic’s historical bike trip data from 2024. The dataset includes details about each ride, such as the type of bike used, ride duration, start and end times, day of the week, and whether the rider was a casual user or an annual member. The data is anonymized and does not include personally identifiable information, ensuring privacy compliance.

This dataset will allow us to analyze the behavior of both casual riders and annual members, focusing on factors such as ride duration, usage patterns, and time of year to identify key differences. By aggregating and analyzing these data points, we can gain insights into how each group uses the service and inform recommendations for converting casual riders to members.

## Data License

The data used in this project is provided under the terms of the [Divvy Bikes Data License Agreement](https://divvybikes.com/data-license-agreement).

# **Data Cleaning & Preparation**
The data used in this analysis was cleaned and prepared using a series of SQL queries. For a detailed list of the queries used to clean and transform the data, please refer to the file linked below:
[SQL Queries for Data Cleaning & Preparation](https://github.com/Data-cat750/analytics-portfolio/blob/main/Cyclistic/SQL)

# **Analysis**
To analyze how casual riders and annual members use Cyclistic bikes differently, I followed a structured approach using the cleaned and prepared data. The key steps in this process were:

Descriptive Statistics: I calculated key metrics such as the average ride duration, number of rides, and peak riding times (by day of the week and time of year) for each group. This helped identify trends and patterns specific to each rider type.

Comparison of Patterns: I compared ride patterns for casual riders and annual members, focusing on variables like:
  Ride duration: Do casual riders take shorter or longer rides compared to members?
  
  Time of year: Are casual riders more likely to use bikes during certain days of the week or seasons of the year compared to members?

  Visualization: I created visualizations to effectively communicate trends and differences between the two groups, making the data easier to interpret.

SQL Queries: For data analysis, I used SQL to process and manipulate the data. For a detailed list of the queries used to analyze the data, please refer to file linked below
[SQL Queries for Data Analysis](https://github.com/Data-cat750/analytics-portfolio/blob/main/Cyclistic/SQL%20Analysis)
