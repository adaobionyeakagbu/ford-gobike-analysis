# Ford Go Bike Data Visualization and Analysis
## by Adaobi Onyeakagbu


## Dataset

> This dataset contains trip details of the Ford GoBike sharing service. Ford GoBike is a company that provides on-demand bike rentals for customers in the Bay Area. The data consisted of 13 main initial variables for data entries in 2017, 2018, 2019 and January-March 2020. All the tables were merged and a 10% fraction of the entire set was finally used to get representation for each year and wrangling was done. The resulting dataset consisted of 512788 instances and 19 attributes with representation of entries from 2017 till March 2020.
The dataset can be found in the repository: [https://s3.amazonaws.com/baywheels-data/2017-fordgobike-tripdata.csv].
Main features focused on
1. User_type
2. Duration
3. Distance
4. Time of day (hour)
5. Day of the week
6. Month
7. Start Station name
8. End Station name


## Exploratory Analysis

> In the exploration, I found that there are more people subscribed to the service (Subscribers) than casual riders (Customers) but customers use the bikes for longer than the subscribers. I also found a strong relationship between user types and the hours, days of the week and the months. Weekend days have half the number of the trips comparing to workweek trips. The start and end of working-hours have the most number of trips and # of hours.
Also, there is a strong relationship between the hours and days of the week.


## Explanatory Analysis

> For the presentation, I demonstrated the influence of user type hourly, daily, monthly and on average trip duration using simple countplots and pointplots. Then I demonstrated the strong relationship between hours and day per user type using a heatmap.

## References
https://www.machinelearningplus.com/plots/top-50-matplotlib-visualizations-the-master-plots-python/#30.-Categorical-Plots
https://stackoverflow.com/questions/19412462/getting-distance-between-two-points-based-on-latitude-longitude
