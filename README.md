# Background

Investors are evaluating a bike-sharing program in Des Moines. One of the key stakeholders would like to see a bike trip analysis. To help solidify the Des Moines business proposal, this analysis uses Pandas and Tableau to create visualizations that will help pitch the business proposal.

## Purpose

The purpose of this analysis is to create visualizations to:

- Show the length of time that bikes are checked out for all riders and genders.
- Show the number of bike trips for all riders and genders for each hour of each day of the week.
- Show the number of bike trips for each type of user and gender for each day of the week.

## Results

[Click here to view the NYC bike story in Tableau.](https://public.tableau.com/app/profile/alejandra8846/viz/nyc_citibike_challenge_16512783716070/NYCCityBike?publish=yes)

### Overview Dashboard

The "Dashboard Overview" shows 4 different visualizations summarizing the dataset that was used for this analysis. The "Gender Breakdown" shows that males make up more than half of the data points. The "Customers" pie chart shows that the majority of the datapoints are subscribers of the "citiBike" membership. The "Number of Rides" number shows that the dataset includes 2.3MM data points. Lastly, the "Top Starting Locations" map shows that the datapoints are from NYC users.

<img src="/Images/data-overview.png">

### Checkout Times for Users

The "Checkout Times for Users" graph shows that, on average, most users checkout bikes for a period of 5 minutes.
<img src="/Images/checkout-times-users.png">

### Checkout Times by Gender

The "Checkout Times by Gender" graph shows that in comparison to males, females tend to checkout bikes for one additional minute (5 minutes vs 6 minutes).
<img src="/Images/checkout-times-gender.png">

### Trips by Weekday per Hour

The "Trips by Weekday per Hour" graph shows that Mondays through Fridays, the most popular trip times are between 7AM-10AM and 4PM-8PM. For Saturtdays and Sundays, the most popular trip times are between 10AM-8PM.
<img src="/Images/trips-weekday-hour.png">

### Trips by Gender (Weekday per Hour)

The "Trips by Gender (Weekday per Hour)" chart shows that the most popular trip times are consistenet between females and males.

<img src="/Images/trips-gender-weekday-hour.png">

### User Trips by Gender by Weekday

The "Trips by Gender by Weekday" shows that Thursdays and Fridays are the most popular days to ride citibikes.

<img src="/Images/trips-gender-weekday.png">

## Summary

In summary, most users checkout bikes for short periods of time. Males tend to ride bikes for 1 minute less than females. It would be interesting to explore if males tend to ride longer distances or if they just ride at a faster speed. The data suggests that Mondays-Fridays users ride bikes to commute to work, as most popular ride hours are between 7AM-10AM and 4PM-8PM. On Saturdays and Sundays, the most popular ride times are between 10AM-8PM, suggesting that users ride for recreational purposes on those days. Thursdays and Fridays however, are the most popular days to ride citibikes. Two additional visualizations for future analysis would be the most popular start and end stations by weekday and by hour for both males and females.
