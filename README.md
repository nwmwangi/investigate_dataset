# (201902-fordgobike-tripdata Data Exploration)
## by (Martha Mwangi)

## Dataset

Ford GoBike System Data is a dataset that consists information of over 180,000 entries about individual rides made in a bike sharing system in San Francisco Bay area. 

## Summary of Findings

In the exploration of these dataset, I found that most trips took place in the month of February with a few trips that had started towards the end of February crossing over to the month of March. Also in the findings, I found out that most trips occurred toward the middle of the week with Thursdays and Tuesday recording a higher number of trips.
It was surprising to find out that weekends, that is Saturdays and Sundays recorded less trips in the shared System.
The findings show a positive relationship between the bike sharing system with the weekdays compared to the weekend.

There was also a Positive relationship between the morning working hours and the evening hours where most trips were registered in the hour of the day distribution.

Away from the main variables of interest, there was also a positive relationship between the user type and gender on the chances of taking a trip with the bike in the shared systems. The findings show that Male subscribers were took the most trips and were highly registered in the days and hours that most trips took place.


## Key Insights for Presentation

For the presentation, I focus when most trips were tsken in terms of time of day, day of the week or month of the year. I start by extracting the hour(s) in which the trips took place from the start_time column, counting the trips registered in the coreesponding hour and plotting the distribution with a bar graph.

I also extract the day of the week and the trips count and plotting the same on a bar graph. For the month's trip distribution I plot a histogram. These makes up the three main variables that influence the frequency of a trip.
Other variables such as the user type and the gender are covered using Clustered plots and Facet grids.