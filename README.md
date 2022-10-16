# (201902-Fordgobike-Tripdata)
## by (Mostafa Elnagar)


## Dataset

The dataset consists of the duration and attributes for 183412 ride covering the greater San Francisco Bay area, and the dataset only includes Febuary, 2019 rides.
The attributes that are included in the dataset are ('duration_sec', 'start_time', 'end_time', 'start_station_id','start_station_name', 'start_station_latitude', 'start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type', 'member_birth_year', 'member_gender' and 'bike_share_for_all_trip')

## Summary of Findings

- On a log-scale the duration as well as the distance distribution formed a normal distribution with most of the values around 10 to 32 mins for duration, 1 and 3 kilometers for the distance.
- the most common ages are between 20 and 40 years old. there are a few outliers for ages greater than 80.
- work days have higher number of rides than weekends.
- the distribution along the day hours is biomodal with one peak between 7 and 9 AM and another peak between 4 and 6 PM.
- the most frequant rides are on working days, the most frequent hours are when workers go and come back from their work. 
- the vast majority of users are males and subscribers.
- there is a correlation between the distance and the duration of the ride when we exclude the durations greater than 130 mins, this correlation vanishes when we include them.
- we might say that rides that take less than 30 minutes are most commonly used as a transportation mostly to work.
- there is no correlation between age and duration.
- it appears to be customer's rides in general are associeted with long duration and long distance than subscriber's, the same goes for females over males and other genders.
- the number of customers isn't affected by the day, in contrast subscribers are more common to ride in working days.
- the distribution of rides over the hours of day is bimodal for all working days and it transforms to unimodal for weekends with one spike between 12 and 5 pm.
- the relationship between distance and duration seem to be linearly correlated for both customers and subscribers, but this relationship becomes weak for custumors and the points becomes more spread.
- the correlation between duration and distance is not affected by user type nor gender.
- the average duration is higher for customers than subscribers, it also has more variation. and the avg duration in general increases on weekends.
- male customers ride bikes for more time than other genders, and male subscribers ride for less time than others.


## Key Insights for Presentation


- work days have higher number of rides.
- The distribution of rides over the hours of day is bimodal for all working days with one peak between 7 and 9 AM and another peak between 4 and 6 PM
- It transforms to unimodal for weekends with one spike between 12 and 5 pm.
- the most frequant rides are on working days, the most frequent hours are when workers go and come back from their work.
- The average duration is higher for customers than subscribers, it also has more variation. and the avg duration in general increases on weekends.

> Probably most of the clients of the bike-sharing busnisses use the bikes as a transportation to go to thier work or school and most of them are regular subscribers.
