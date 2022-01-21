# PyBer Analysis
## Overview
This week we helped the CEO of Pyber, a ride sharing service (not to be mistaken with Uber), understand the differences in the number of rides taken, the total drivers available, and the price fares based on if the ride was taken in a urban, suburban, or rural environment.  We based our analysis on two set of data: one containing information about each city- what type city and how many drivers it has; and the other that recorded every ride in the year 2019- where and when it took place, and how much it cost.  

Upon completing this analysis, we created two artifacts: 
1. A summary data frame that quantifies the total & average number of rides and drivers, and fares by city type in 2019.
2. A line chart to better display the differences between each city type's sum of fares from January 2019 through April 2019.

We ran this analysis so that PyBer can make data-driven decisions on how to increase both access and affordability of their services to their customers.  

## Results 
Thinking about the history of rideshare services, it's not shocking that we see a **higher useage of PyBer in urban cities than we do suburban and rural areas.**  For example, taxi services have always been most popular in large metropolitain cities, like NYC where the yellow taxis have become part of the city's brand (think about how many NYC snowglobes tshirts you've seen with a taxi in them).  This may be becasue these metropolitain areas are commonly more walkable than other city types so residents see less of a need to own a personal vehicle.  However, most urban residents aren't superhuman and can't walk *everywhere*, so, they rely on public transportaion methods like subways, ferrys, and *rideshare services like PyBer*.

That being said, let's take a look at differences of rides, drivers, and fares for each city type.   

![pyber_summary_df](https://user-images.githubusercontent.com/94569240/150586098-12b89529-369d-4288-8dc5-f8d74deb3568.PNG)


#### Total Rides, Drivers, and Fares per City Type
In the first column, "Total Rides", of the dataframe shown above, we see the total number of rides taken in each city type in 2019.  The total number of urban rides is **almost 3x larger** than the total rides in suburban cities and is **13x larger** than those in rural ones.

We see the same trend in the second column, "Total Drivers" as well.  The total number of urban drivers is **nearly 5x larger** than the amount in suburban cities and **30x larger** than those in rural areas.  

The third cloumn in the data frame above, "Total Fares" dipcts the amount of money spent by PyBer users on ride fairs in 2019.  Despite urban rides, on average, costing less (column 4, Average Fare per Ride), urban rides still grossed just over **20,000 dollars more** than suburban fares and **35,000 dollars more** than rural ones.

We can visualize this gap better with the line chart we created that displays each city type's sum of fares for the first few months of 2019- January through April.  

![PyBer_fare_summary](https://user-images.githubusercontent.com/94569240/150586141-84e451b2-fce4-4c35-adb6-9428bd5ed7c1.png)

Visualizing the data this way helps puts into perspective just how big the differences are between the sums of fares for each city type.  

However, this chart is not only good for looking at the three city types together, it's also useful to see the trends for each city on it's own.  For example, we can also see that urban fare totals begins to decrease significantly in mid-april.  I'm curous to see if this trend continues downward or remains lower, through the rest of Q2 as it gets warmer, only to rise again in Q3 as we enter the fall and winter months.       
  
#### Average Fares per Ride and per Driver by City Type

As alluded to above, the fourth column, "Average Fare per Ride", of the summary data frame shown above depicts rides in urban areas to be the cheapest of the three.  **Rural areas cost about 3.50 dollars more than rides in suburban cities and just over 14.00 dollars more than rides in urban landscapes.**  

Again, the same trend is seen in the fith column, "Average Fare per Driver".  However, the gap is much wider with **rural fares per driver costing about 16.00 dollars more than in suburbia and just under 39.00 dollars more than in urban ciites.**


## Summary 
Based on my findings, I believe the differences in total and average rides, drivers, and fares are the result of supply and demand.  Again, rideshare services have always been more popular in urban cities.  Thus, there is going to be more drivers in those areas, which allows for more rides to be taken, and as there are more rides being taken from more drivers, the fare costs are driven (pun intended) downwards and become more affordable.

We see the opposite effect for rural areas on the other end of the spectrum.  Rural areas are more spread out, so, more residents own personal vehicles they can use to get themselves around.  When this is the case, the demand for a rideshare service decreases, total drivers become more scarce, and then the rides cost more.  

Based on these disparities, I have three reccomendations for the CEO of PyBer that might increase the accessibility and affordability of its services to customers.  

#### Three Business Reccomendations 
1. Start by incentivising your new and exisiting urban drivers to take rides in *both* their urban city and the surrounding suburb(s).  Then, do the same for new and exisitng suburburban drivers to venture out into the surrounding rural areas.  

*This will increase the supply of drivers/available rides in the lower performing areas which will inturn decrease the average fare per driver metric in these cities and make this service more affordable.*

2. We know that supply can directly impact demand- if rides are more freuently available, suburban and rural residents may be more likely to to take PyBer because they don't have to work as hard to search for a driver.  So, once the supply is increased like in suggestion #1, you'll want to kickstart the demand as well.  To do this, I reccomend running promotions for just rural and suburban ares to incentivise residents to use PyBer.  If anything, this will increase brand awareness and, while someone might not become a customer instantly, they'll know they can use PyBer when they eventually need an alternative means of transportation.  

*This will increase the demand/total number of Pyber rides taken in the lower performing areas which will inturn decrease the average fare per ride metric in these cities and make this service more affordable.*

3. Lastly, even though the urban citites consistently perform the best of the three types, I reccomend that the CEO look into the sudden drop in total fares for Urban areas in mid-April.  The CEO should compare 2019's data to years' past to see if this is a common and expected drop as colder states start to get warmer, or, if something happened specifically in 2019 to cause PyBer usage to drop.  Either way, knowing the reason will help PyBer strategize options of how they can avoid this sudden fall in the future.    
