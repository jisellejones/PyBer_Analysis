# PyBer_Analysis

## Overview

We analyzed the 2019 ride share data to determine the weekly fares in different types of cities (rural, suburban, and urban). The purpose of this analysis is to help PyBer improve business decisions.

## Resources

- Data source: city_data.csv & ride_data.csv
- Software: Python 3.7.10, Jupyter Notebook, 6.3.0

## Results

The analysis showed that in 2019 there were about 6 times and 16 times as many total rides in the suburban and urban cities than in the rural cities. In the urban cities there were about 50% more drivers as there were number of rides while in the suburban and rural cities there were fewer drivers than there were rides. 

The average fare per ride was $10 less in urban cities than in rural cities. The average fare per driver in rural cities was more than 2 times the average fare per driver in urban cities and more than 3 times the average fare per driver in urban cities (see figure 1). 

Even though drivers made a significant amount more on average in rural cities, when determining the sum of the total fares for the three types of cities, the total sum for urban cities was about 9 times as much as the total sum of fares in the urban cities.

*Fig 1*

![summary_data_frame](https://github.com/jisellejones/PyBer_Analysis/blob/main/analysis/summary_data_frame.png)

When analyzing the weekly data for the first quarter in 2019, the data showed that the total overal fare for urban cities per week was significantly higher than the other types of cities (see figure 2). There were similar increases in the fare amount in the third week of February for all three types of cities and a dip in the fare amounts in March. However, the fare amount each week maintained large gaps between the amounts each week with no overlap.

*Fig 2*

![lineplot](https://github.com/jisellejones/PyBer_Analysis/blob/main/analysis/line_plot_fare_type.png)


## Summary

It is clear from the data that while the average fare per ride is significantly less in urban cities, the amount of total fares is significantly greater in urban cities than in suburban or rural cities. This could be due to the larger population of people in urban cities. This could also be due to the lack of automobile ownership in urban cities. Paying for a ride may be more economical than paying for a car payment and the headache of maintaining a car. There also tends to be more space between locations in rural cities which may make rides longer and thus more expensive.

There are far fewer drivers in rural and suburban cities than rural cities which may be another factor in why rides are so expensive in these types of cities. Because there are fewer drivers in rural and suburban cities, causing the fare for rides to increase due to the demand for drivers. Urban cities seem saturated with drivers, causing the demand for drivers to decrease resulting in lower fares per ride.

It would be interesting to dive further into the data to see in which sections of the different cities rides tend to be more popular. This could give greater insight into where customers are located and how to market in different types of cities. 


### Limitations

It is unclear how this data was gathered, so we can not vouch for the validity of the data.