

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

Descriptive Statistics: I calculated key metrics such as the average ride duration and peak riding times (by day of the week and time of year) for each group. This helped identify trends and patterns specific to each rider type.

Comparison of Patterns: I compared ride patterns for casual riders and annual members, focusing on variables like:
  Ride duration: Do casual riders take shorter or longer rides compared to members?
  
  Time of year: Are casual riders more likely to use bikes during certain days of the week or seasons of the year compared to members?

  Visualization: I created visualizations to effectively communicate trends and differences between the two groups, making the data easier to interpret.

SQL Queries: For data analysis, I used SQL to process and manipulate the data. For a detailed list of the queries used to analyze the data, please refer to file linked below
[SQL Queries for Data Analysis](https://github.com/Data-cat750/analytics-portfolio/blob/main/Cyclistic/SQL%20Analysis)

# **Summary of Analysis**
The analysis of Cyclistic's bike-share usage revealed several key insights into the behavior of casual riders versus annual members:

Ride Duration: On average, casual riders tend to have longer rides than annual members. Casual riders record an average of 22.1 minutes per ride, almost double the 11.7 minutes per ride of members. This suggests that casual riders may be using the bikes for leisure, while members may be more focused on commuting or short-term usage.

Ride Frequency and Timing:
Casual riders tend to use bikes more frequently on weekends, which aligns with the idea that they are more likely to use the bikes for recreational purposes.
In contrast, annual members use the bikes more during weekdays, indicating that they might be using the bikes for daily commuting or work-related trips.

Seasonality:
Summer is the most popular season for bike rentals, with both casual riders and annual members showing a noticeable spike in usage.
Winter sees a significant drop in bike rentals overall. However, interestingly, annual members recorded 274,513 more rides than casual riders during the winter season, highlighting their consistent usage even in colder months.

Distance Traveled: Despite the differences in ride duration and frequency, the distance traveled by both casual riders and annual members is about 2.1 km, indicating that both groups tend to use bikes for similar distances on average, even if the ride duration varies.


# **Data Visualizations**

This chart compares the number of rides taken by members and casual riders across each day of the week.
[Day of the Week, Member vs Casual Rides](https://public.tableau.com/views/BikeRentalsbyDayAComparisonofMemberandCasualRiders/Sheet3?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

This chart compares the number of rides taken by members and casual riders across different seasons.
[Seasonal, Member vs Casual Rides](https://public.tableau.com/views/BikeRentalsAnalysis_17387987204010/Sheet3?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

This chart compares the average ride time by member and casual riders. [Average Ride Time Member vs Casual](https://public.tableau.com/views/BikeRentalsAnalysis_17387987204010/AVGRideTime?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

# **Recommendations**

Recommendation: Focus on casual riders who use bikes more frequently on weekends. Since casual riders tend to ride more on weekends, offering weekend-specific promotions can encourage them to see the value in a membership.

Next steps: Run weekend promotions that offer discounted annual memberships or exclusive weekend ride perks to casual riders. By highlighting the added benefits of being a member, such as the ability to ride whenever they want.

Recommendation: Use the peak riding season (summer) to capture more casual riders by offering exclusive membership promotions.

Next steps: Provide summer-only membership discounts or free trial periods to casual riders during the busiest season. This capitalizes on the high demand and gives casual riders a taste of the full membership experience, increasing the chances of conversion.

Recommendation: Leverage your existing members to bring in new ones. People are more likely to try memberships when they hear positive recommendations from those they trust.

Next steps: Introduce a referral program that rewards current members with free ride credits or discounts on membership renewals for successfully referring casual riders to become members. This creates a viral effect, where current members act as advocates for the benefits of membership.

Yes, adding a conclusion is a great way to wrap up your analysis and leave the reader with a clear, concise summary of your findings and recommendations. Your conclusion should briefly summarize the key insights and reinforce the importance of implementing your recommendations.

Here’s a suggestion for your conclusion:

# Conclusion
In summary, the analysis of casual and member riders reveals key differences in behavior that can be leveraged to increase membership conversions. By focusing on weekend riders, offering targeted promotions, and emphasizing the value of membership, the business can successfully shift more casual riders to become long-term members. Implementing these strategies, alongside continual monitoring and adjustment based on rider behavior, will help ensure sustainable growth and customer loyalty.
