# Ford GoBike Data Exploration
## by Tella Adetayo


## Dataset

Ford GoBike is the Bay Area's bike sharing system. Bay Area Bike Share was introduced in 2013 as a pilot program for the region, with 700 bikes and 70 stations across San Fransico and San Jose. 

The programs consists of bikes which are specially designed that can be locked in a network of docking station, it can be unlocked in one station and locked in another station. The bikes are available 24 hours per day, 7 days per week and 356 days a year. The dataset was sourced from one of the datasets provided by udacity which was downloaded from here[https://video-udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv]

In the Part 1 which is the Ford GoBike Data Exploration, i did some data wrangling and exploration using python and the dataset(Ford GoBike) contains:
- Ford GoBike dataset have 174,952 rows after some wrangling and 19 columns. The columns are duration_sec and bike_id which the datatype is int64, start_time and end_time which both their datatype are in datetime, user_type, member_gender and bike_share_for_all_trips are in category while start_station_id, start_station_name, start_station_latitude,start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude are float64, the weekday_name is in object and the hour column is in int64.

In the Part 2 which is the Ford GoBike Exploration, i produced a presentation of some of the visualizations created in the part 1 during the exploration.

## Summary of Findings

In the exploration, I found that the male genders are more likely to take a rides than any other genders, I also found that the Customers  which are the low user go on a longer trip than a Subscribers who are the large users and i also found that the market is the most common place for starting every rides and the second most common place for ending rides.

I also found that the peak of every rides during the hours occur twice which are 8am in the morning and 5pm in the evening which is more likely to be the time when people are either leaving home and coming back home.


## Key Insights for Presentation

For the presentation, I am trying to investigate what day of the week has the highest starting times per rides, what is/are the peak of the highest starting times for every rides, what gender took the most trips throughout the year, what are the top 10 station for starting trips and What is the average duration per minutes for every rides by user.
