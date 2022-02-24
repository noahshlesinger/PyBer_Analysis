# Pyber Analysis
The purpose of this analysis is to summarize fare prices, the number of drivers, and the number of riders in a list of cities that are categorized into 3 city types:"Rural", "Suburban", and "Urban" for cross comparison. This comparison will aid decision-makers at Pyber know where they need to push more resources for maximal effectiveness and profits.

## Results:

The first place to start is the total rides, total drivers, and total fares across all three city types to get an understanding for the spread of resources and profits. The table below shows a clear increase in all three metrics as the population increases from "Rural" to "Suburban" and "Urban". It is logical to see a greater number of drivers in the same area with more riders whom request more rides, resulting in greater profits from a greater number of total fares. 


![Total Rides, Drivers, and Fares across the three city types](https://user-images.githubusercontent.com/95305584/155456956-cbe3e9c9-72e4-4e90-b532-4b6eecc8a034.png)

However, this only show isolated relationships. By dividing the total fares by the total rides and again by the total drivers, there is an opposite trend in which the less populated areas have increased costs per driver and rider. The table now includes the average fares per driver and per ride. The increase in cost per driver is very sharp from the Urban city type of $0.67 to the Rural city type of $8.06. The average fare per rides is less steep but still very noticable. With fewer drivers and likely longer trips in the rural communitites, one would expect to see greater prices. There are fewer drivers available to take the passengers and if it takes more time of the driver's time for a single ride, the fare would incfrease accordingly.  

![Pyber_summary_df_all](https://user-images.githubusercontent.com/95305584/155457677-a46ab145-9be9-4142-8ae1-fcf426904d40.png)

At first, there seems to be a need to increase business in the rural areas due to the greater return on investment, however, it  only accounts for $4,327.93 compared the nearly $60,000 brought in by the other two. That comes to roughly 6.5% of total sales. Additionally, with high ride fares, riders in rural areas are already paying a high price and may be easily persuaded to switch from PyBer to another company if the fares increased further. Instead it would makes sense to keep the focus on large number of riders bringing in $39,854.38. Small changes made in the urbna areas could multiply quickly to greater gains. 

To visualize this relationship between the 3 city types, the first 4 months of 2019 data is plotted below.

![FigTotalFarebyCityType](https://user-images.githubusercontent.com/95305584/155458858-bf33a816-e17a-40b1-ae75-e526408ed667.png)

While this graph might feel redundant, there is always a good reason to look for trends over time and over the course of the year. Here, there are slightly increases and decreases in total fares across the months, but overall, they are steady in values. The exception is at the beginning of the year when theere is an incerase in Total Fares in the Suburban and Urban cities but not in the Rural community. At the end of April, there is a similar increase in Suburban fares but constant total fares in the Urban and Rural city types. This demonstrates that there are the greatest fluctuations in total fares in the Suburban city type, followed by Urban city types and lastly by the Rural city type.  This may indicate that Suburban areas have the greatest areas for improvement to keep consistent revenue as well as the Urban city types. The Rural ares seem to be more independednt of the time of year and the changes in fares are less extreme. The only exception to this s the beginning of March, but it is anyone's guess as to the reason for the uptick in total Fares across all the city types.

## Summary:
 Following the analysis presented above, here are 3 recommendations:
 
 1. Increase the cost  of the fares per ride in the Urban city types by a small amount that won't be sufficient to cause customer dissatisfaction. A small increase will not make a difference for a single ride, but across all the rides there will be a significant incresae in profits.
 2. Incresae the cost of fares marginally in the Suburban and Urban areas at the beginning of the year and reap the benefits of greater rides requested. The general population will be returning to schools, work, home, etc. and the demand for rides will increase. Assuming the number of drivers stays constant, this will result in greater profits.
 3. Increase the number of drivers in the Suburban areas in general and especially in the high volume times of early January and the late spring. The cost per driver is close to nothing when compared to the fares and could bring up revenue easily. Doing the same in the Urban city types would be pointless as there are already too many drivers in the bigger cities.

