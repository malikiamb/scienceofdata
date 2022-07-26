Fordgobike Data Exploration

## Dataset

TThis is the exploration of February 2019 user data for fordgobike located in
the greater San Francisco Bay Area. Fordgobike is a bikesharing system allowing
users to rent bikes based on their needs with the ability to
subscribe or take advantage of one-time usage.
repository for data [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv),

## Libraries used

Numpy, pandas, matplotlib, seaborn, calendar, time, math & datetime

## Noteboook entitled
Ridershipexploration

## Summary of Findings

Initial programmatic assessment revealed that this dataset includes 16 features
and 183,412 rows.  User types are broken into subscriber and customer.
There is also information on gender, birth date, duration of rental and start
and end points.  Wrangling steps involved adjusting data types, reviewing
outliers, null values, dropping columns that were not going to be utilized
and adding columns with calculated metrics for ease of analysis.


In addition to main features, I explored time of day to see when most rides
occurred.

•	Youngest rider is 18 and the average rider is 34 years of Age
•	89.2% of users are Subscribers most trips fall below 20 minutes
•	The least amount of rides occur at night by both customers and subscribers
•	Males account for 71% of total riders
•	The most popular rental hour is 17:00 for both male and female users
•	Users above the average age of 34 are not subscribers
•	Users above the average rode mostly in the morning and afternoon 
•	Customers use bikes for longer than subscribers with some over 20 minute



## Key Insights for Presentation

1.	Overall, subscribers were the largest user and were consistent in primarily
riding in the Morning and Afternoon.
2.	Customers exceeded the average rider time of 11 minutes while subscribers
remained consistent with short ridership
3.	Males were dominate at 71% of total users and they took the most rides at
17:00 Although females peaked at the same time


## Blogpost Bikeshare Ridership Exploration

https://medium.com/@melthompsonb/bikeshare-ridership-exploration-b6885bc07c3a
