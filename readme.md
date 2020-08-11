# Exploring the Latest Dataset from Lyft-Bikes (06/2020)
## by Juan Garcia


## Dataset

The dataset can be found on the lift webesite - [just follow this link](https://s3.amazonaws.com/baywheels-data/index.html). It contains more than 100 Tsd. anonymized entries - each for the renting of a bike. Our variables of interest are:
- The time spent riding (ride duration)
- The hour of the day in which the customer rented the bike (hour of day)
- The day of the week in which the customer rented the bike (week day)
- The type of the customer (member or casual)
- The type of the bike (electric or standard)

Other variables that could explain the variation on the ride duration, such as weather, neighborhood, special offers and so on, are not included in this analysis and remain open for furhter research


## Summary of Findings

Our variable of interest is the ride duration, since it is a good proxy for the revenue of lyft (bike sharing company). To understand the variation we plot its behavior compare to other variables. We discover a couple of things:
- The type of customer seems to have a direct impact in the average time spent riding
- The hour of the day a customer rents a bike seems to have an impact in the average time spent riding. However, not as strong as expected, as most of the bikes are rented during the day. Nevertheless, it seems that night rides are much longer
- The day of the week a customer rents a bike seems to be important, but we only have to differentiate between weekdays and weekends, as the variation during weekdays seems to be very low
- The type of bike seems to have no impact on the duration of the ride

All this findings remain as hypothesis and need to be tested to confirm any statistical significance. Furthermore it would be very interesting to build a prediction model for the duration of the ride. However, there are many more variables that need to be included, for example the weather, the neighborhood, the month, the number of bikes available, the population density and so on. This remains open for further research


## Key Insights for Presentation

The presentation focuses on the key findings: The most important variables are the type of customer, the hour of the day a bike is rented and if that day was a weekday or the weekend.

As said before a statistical analysis of this findings are necessary to validate them.
