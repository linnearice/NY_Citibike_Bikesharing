# Bikesharing

## Overview

This project is an analysis of New York Citi Bike data, using data visualization tools to explore the viability of a bike-sharing business in Des Moines.

## Link to Tableau Public Story Presentation and Other Resources

* Tableau Dashboard and Story Presentation:  https://public.tableau.com/app/profile/linnea.b.rice/viz/CitibikeChallenge_16369137968740/Story1?publish=yes
* Dataset: provided by Citibike website for New York City August 2019 trip data - 201908-citibike-tripdata.csv.zip
https://s3.amazonaws.com/tripdata/index.html
* Software:  Python 3.7.6 and Tableau Public 2021

## Results

The charts below represent an overview of the NYC Citibike data.  There are a total of 2,344,224 bike trips in the month of August 2019.  The largest user type is by far the subscriber group with 81% subscribers and random customers represent only 19% of total users.  For users by gender, the majority are male users at 65% followed by females at 25% while 10% are unknown.   

![2021-11-16](https://user-images.githubusercontent.com/35401581/142051419-3a3d144b-4087-424c-b5ef-4a8611b244ef.png)

The charts below represent:
* Average Trip Duration by Hour - there are some spikes in the data but overall the pattern of use among varying age groups appears to be fairly evenly distributed.
* Average Number of Rides by Hour - the highest usage times are between the hours of 5pm to 7pm and 7am to 8am, respectively.  This pattern appears to depict a workday routine.  Perhaps further study could be done to see if this routine is represented Monday through Friday.  The weekends may show a different trend. 

![2021-11-16 (1)](https://user-images.githubusercontent.com/35401581/142044297-4812ccb1-bec5-4fee-9d7e-54215154f033.png)

These charts following represent how long the average checkout times were by user and by gender.  No matter the day or gender, the average bike trip is 30 minutes or less.

![2021-11-16 (2)](https://user-images.githubusercontent.com/35401581/142045097-ec9d0871-57db-4e07-8d86-e20bd547208a.png)

This chart below represents bike trips by weekday per hour and supports the hypothesis in prior analysis where weekend userage is scattered throughout the day while weekday userage is concentrated around rush hour and most prevantly during the afternoon hours between 5pm to 7pm.

![2021-11-16 (3)](https://user-images.githubusercontent.com/35401581/142045119-ede70bac-4cdb-4662-92b0-6f48bdfb3c1b.png)

The chart above was expanded upon to include bike trips by weekday by hour and by gender as well and is presented below.  This analysis shows the same usage trends as above.  There appears to be no difference in hour of usage between the gender groups with the exception that males have higher usage, but again the hours are concentrated at rush hours during the week and all throughout the day on the weekends.

![2021-11-16 (4)](https://user-images.githubusercontent.com/35401581/142045133-0c717b01-60d8-4b03-b320-717e83e64b88.png)

The chart below represents weekday trips by user type by gender.  As indicated in earlier charts subscribers represent 81% of the market.  This chart indicates the highest usage day is among subsribers on Thursdays with 259,316 male users.  Females represent a lower number of usage on Thursdays with 88,281 users for comparison.  The usage among random customers appears to be steady throughout the week with slightly higher usage on the weekends. 

![2021-11-16 (7)](https://user-images.githubusercontent.com/35401581/142045160-348d8ada-e389-4e88-8bbd-7afe2ce82a44.png)

This chart below depicts a map of the prevalence of bike trips made at their starting point in the New York City area.  The highest concentration appears to be in the tourist areas and also the heart of NYC's business district.  Some of the highest starting locations show roughly 13,000 users while some of the less popular locations are roughly 2,000 users.   

![2021-11-16 (6)](https://user-images.githubusercontent.com/35401581/142045172-ac8ef3a8-2b6f-455d-b889-aedc6ca3c961.png)

## Summary
* The data supports strong usage and high popularity in the New York City area for the month of August.
* The visualizations are helpful in seeing several user patterns:
    - the majority of users are male
    - the majority of users are subscribers
    - the majority of usage is in the rush hour timeframes during the work week
    - weekends still appear to have strong steady usage throughout the week with a slight uptick on weekends Saturday and Sunday
    - the higher usage areas appear to be the central business district and tourist areas

In general, this analysis supports implementation in the Des Moines area perhaps following the same guidelines as NYC Citibike.  That is, implement a program that supports subscribers versus random customers, target male users primarily, research areas in the city to install the bikes such has the downtown business district, etc.

## Further Analysis
* One item to consider for further study is the cost to ride and how does it compare to other forms of transportation such as the city bus, etc.
* Further analysis should also be conducted to review the slower winter months to determine the viability of the bike market throughout the year.         
