# NYC Citi Bike Trip Data Analysis

## Overview of the Analysis

The purpose of this data analysis is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, trip data from New York Citibike for the month of August, 2019 has been chosen to perform analysis and create a set of visualization in **Tableau** to highlight the following findings:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

## RESULTS 

## Steps of Analysis - D1:

At first, the NYC Citibike trip data for the month of August 2019 has been imported to a *jupyter notebook* **NYC_CitiBike_Challenge** and the *tripduration* column datatype has been changed from *integer* to *date-time* format bu using Pandas **to_datetime()** method with `unit='s'`. The new DataFrame with converterd `tripduration` columns has been exported to *"201908_citibike_datetime.csv"* (as shown below) which is them imported to Tableau for further analysis.

![citibike_datetime_to_csv](https://user-images.githubusercontent.com/58155187/130197473-3a0d08bb-207f-45a2-b4e0-abd8d3bc929a.png)

## Steps of Analysis - D2:

### Total No. of Rides

There had been a total of **2,344,224** bike rides in the month of August, 2019.

### Rider Types

There were almost 1.9 Million riders (which is **81%** of total bike riders) who had long-term subscription for citibike riding. Rest 19% are non-subscription regular riders.

In terms of **Gender**, 1.53 Million riders are Male and 0.59 Million riders are Female.

### Peak-hours for bike-trips in August-2019

It looks like 5 p.m. to 7 p.m. in the afternoon, and 8 a.m. to 9 a.m. in the morning are typically peak-hours for bike-trips.

![August_peak_hours_biketrip](https://user-images.githubusercontent.com/58155187/130202087-a83a7a96-fdee-4513-80e2-20fdcaed6ea2.png)

### Top Ending Locations

From the Tableau worksheet, we see that Manhattan is one of the most popular ending locations for Citibike riders.

![top_ending_locations](https://user-images.githubusercontent.com/58155187/130202759-bf047923-3f05-42cb-a784-46f5aa3bd08b.png)

### Checkout Times for Users

In this visualization, we can see the length of time that bikes are checked out for all riders. Most of the riders have trip duration around **5 minutes**.

![trip_duration_all_users](https://user-images.githubusercontent.com/58155187/130204155-f7fd5c5c-c5b7-4e03-abe3-ab0fbb4ac219.png)

### Checkout Times by Gender

Gender-wise Male riders are more than 3-times in number than that of Female riders.

![trip_duration_gender](https://user-images.githubusercontent.com/58155187/130204972-592e5387-c9e2-47ba-9c23-64c1c0eee685.png)

### Trips by Weekday per Hour

Thursday 5 p.m. to 7 p.m. shows the highest number of bike trips.

![weekday_trip_per_hour](https://user-images.githubusercontent.com/58155187/130205523-b05fb145-2613-49ab-8e9b-21c3561d8abb.png)

### Trips by Gender (Weekday per Hour)

As shown earlier, Male had significantly higher bike trips than Female and others.

![weekday_trip_per_hour](https://user-images.githubusercontent.com/58155187/130205993-e69fd94d-2513-4ef4-a361-3a092fd1006d.png)

### User Trips by Gender by Weekday

This analysis shows the number of bike trips by gender for each hour for each day of the week as a heatmap.

![user_trips_gender_weekday](https://user-images.githubusercontent.com/58155187/130206401-66bb25a9-8f2a-44e4-8d17-03be702b550f.png)

## Steps of Analysis - D3:

### NYC Citibike Trip-data Analysis: STORY in Tableau

A story board is created with all the worksheets prepared to visualze different scenario to understand the NYC Citibike trip pattern.

![NYC_trip_analysis_STORY](https://user-images.githubusercontent.com/58155187/130206968-0eaa5ae1-bb67-4515-9ed4-4aaceab0a331.png)


## Summary

From the Citibike trip-data analysis two key findings can be summarized as follows,

- Average trip duration is slightly higher for younger riders, which varies from 10 to 20 minutes.

![avg_duration_by_age](https://user-images.githubusercontent.com/58155187/130207886-2d866f88-6dd8-4f74-acc2-bddbe51bcb46.png)

- Peak hours for bike trips looks like 5 p.m. to 7 p.m. in the afternoon, and 8 a.m. to 9 a.m. in the morning.

![peak_hours](https://user-images.githubusercontent.com/58155187/130208476-b0e7d9e1-7e98-427f-bf5e-ccd3cadaa350.png)




#### Cotact:

m.a.moonem@gmail.com 
