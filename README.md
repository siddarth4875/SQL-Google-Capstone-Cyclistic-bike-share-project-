# SQL_Google_Capstone_Cyclistic_bike_Share_Project
Google Data Analytics Capstone: Cyclistic Bike-Share Case Study

Ask

Business Task

Cyclistic is a bike-share company in Chicago with a fleet of 5,824 bicycles and 692 docking stations. The company offers flexible pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders, while those who purchase annual memberships are Cyclistic members.

The business task is to design marketing strategies aimed at converting casual riders into annual members. To achieve this, we need to understand how annual members and casual riders differ in their bike usage.

Key Stakeholders

Lily Moreno: Director of Marketing

Marketing Analytics Tea

Executive Team

Prepare

Data Source

The data used for this analysis is Cyclistic's historical trip data from January 2022 to December 2022, available at divvy-tripdata.

Data Description

Number of Files: 12 CSV files (one for each month of 2022)
Columns:
ride_id: Unique identifier for each trip
rideable_type: Type of bike (e.g., classic, electric, docked)
started_at: Start time of the trip
ended_at: End time of the trip
start_station_name: Name of the starting station
start_station_id: ID of the starting station
end_station_name: Name of the ending station
end_station_id: ID of the ending station
start_lat: Latitude of the starting location
start_lng: Longitude of the starting location
end_lat: Latitude of the ending location
end_lng: Longitude of the ending location
member_casual: User type (member or casual)
Tools Used
SQL: For data manipulation, cleaning, and transformation,Data Analyze
Tableau: For data visualization and creating dashboards
Process
Data Combination
Combined the 12 CSV files into a single dataset to analyze the entire year's data.
Data Cleaning
Removed duplicate rows
Handled missing values (e.g., removed rows with missing start or end station names)
Ensured data consistency (e.g., converted ride_length to numeric)
Data Transformation
Added calculated fields:
ride_length: Duration of the trip in minutes
day_of_week: Day of the week for the trip
month: Month of the trip
Data Validation
Verified data integrity (e.g., no negative ride lengths, consistent date formats
Analyze
Key Question
How do annual members and casual riders use Cyclistic bikes differently?
Findings
Ride Frequency:
Members account for approximately 59.7% of all rides, while casual riders account for 40.3%.
Ride Duration:
Casual riders have longer average ride times (19.64 minutes) compared to members (10.74 minutes).
Temporal Patterns:
Casual riders are more active on weekends, while members ride more consistently throughout the week.
Peak months for both groups are summer months, with July being the busiest.
Spatial Patterns:
Casual riders tend to start and end trips near parks and recreational areas.
Members tend to use bikes for commuting, with trips starting and ending near residential areas and workplaces.
Bike Type Preferences:
Both groups prefer classic bikes, but casual riders also use docked bikes, while members primarily use classic and electric bikes
Share
Visualizations
A Tableau dashboard was created to visualize the key findings. It includes:
Bar Charts:
Ride frequency by month
Ride frequency by day of the week
Ride frequency by hour
Line Chart:
Trends in average ride duration over time
Map:
Most popular start and end stations for members and casual riders
Pie Chart:
Distribution of bike types used by members and casual riders
Tableau Dashboard Link
Note: Replace "your_name" with your actual name or handle.

Act
Recommendations
Based on the analysis, the following marketing strategies are recommended:
Targeted Promotions:
Offer discounts or special promotions for casual riders who take longer rides, as they are more likely to benefit from membership.
Seasonal Campaigns:
Launch marketing campaigns in spring and summer when casual riders are most active.
Weekend Focus:
Emphasize the benefits of membership for weekend usage, as casual riders are more active on weekends.
Bike Type Marketing:
Highlight the availability of different bike types, especially docked bikes, which are popular among casual riders.
Location-Based Marketing:

Target marketing efforts near parks and recreational areas where casual riders are more likely to start and end their trips.

Conclusion

This analysis provides valuable insights into the differences between annual members and casual riders at Cyclistic. By understanding these differences, the marketing team can develop targeted strategies to convert casual riders into members, thereby increasing revenue and customer loyalty.
