# (Fordgobike-tripdata Exploration)
## by (Azeez Yetunde)


## Dataset

The dataset, 2019-fordgobike-tripdata.csv was downloaded from Udacity materials. The dataset consists of 183,412 rides  made in a bike-sharing system covering the greater San Francisco bay area with 15 features. During the data wrangling stage, I replaced the missing values in the member_gender column with other. I also replaced the missing values in start_station_name, start_station_id, start_station_id, end_station_id, end_station_name and member_birth_year with their respective modes. I created exra columns for member_age, duration_min, start_month, start_day, start_hr, start_min, end_day, end_month, end_hr and end_min. Then my data exploration analysis was performed with the dataset



## Summary of Findings

For the Univariate Exploration: Most of the trips for both start and end days were on Thursdays while weekend (Saturday) has the lowest trip.I also found out that the subscribers were more than the customers user type. The Age Distribution plot was right skewed with a long tail on the right and majority of the user's ages are between 30 and 39 years old. After a log transformation was done, it also showed that majority of the user's ages are between 30 and 35 years old. The Distribution of the Duration of Trips showed that the plot is right skewed with a long tail on the right.  After a log transformation was done, it showed that most of the duration of trips fall under 500 seconds and it follows a normal distribution.

For Bivariate Exploration: Customers go on longer trips than the subcribers since the cutomers has the highest trips. The ages of the customer type are more than the subscriber type. The male gender travelled the longest trip followed by the female gender and then the other gender. No relationship exists between the members age and the duration of trips travelled. And then most of the members did not share their trips.

For Multivariate Exploration: Customers travelled the longer distances during the weekday but travelled the longest distances during the weekend (Saturday) while subscribers travelled the shortest distances during the weekday but travelled little more distance on weekend (Saturday. The other customer type travelled the longest distances followed by the female customer type and then male customer type. The male subscribers followed by the male customers travelled the longest distances then the female subscribers and so on. There is no correlation between any of the variables and time (duration_min and duration_sec). Finally, There is a strong correlation between start_station_longitude and end_station_longitude and between start_station_latiitude and end_station_latitudeitude. There is a weak correlation between member_age and duration_min, start_station_latiitude, end_station_latiitude.



## Key Insights for Presentation

For the user types, Customers go on longer trips than the subcribers. Also, For the user types, Customers go on longer trips than the subcribers. Also, Customers travelled more distances during the weekday but travelled the longest distances during the weekend (Saturday) while subscribers travelled the shortest distances during the weekday but travelled little more distance on weekend (Saturday). Thefore, the reasons for this should be figured out.

