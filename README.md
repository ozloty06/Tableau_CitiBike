# Tableau_CitiBike


### Resources
- Tableau Public, version 2021.2
- Pandas and Datetime in Jupyter Notebook, version 6.1.4



### Analysis Overview
Opening a midwestern bike share program in Des Moines, Iowa, is an exciting prospect for a couple friends inspired by their use of citibike in New York City. To be sure our angel investors have the best sense of this market, we analyzed data from citibike in order to consider how these findings may apply to our bike share venture. Our data was visualized in Tableau Public in order to create a storyboard to share with interested investors. Our results are shared below.



### Results
#### General Customer Data
![Image of General Customer Types](https://github.com/ozloty06/Tableau_CitiBike/blob/main/Customer_Segments.png) 
Citibike customers are segmented into subscribers or non-subscribers (called "customers"). The majority of citibike users are subscribers (over 81%) which may have an economic advantage for frequent users who may rely on the bike share program for communiting in New York City.


![Image of General Customer Types](https://github.com/ozloty06/Tableau_CitiBike/blob/main/Customer_Gender.png)
When it comes to gender, 65% of citibike users are male, 25% are female, and the rest are unknown gender. It is unclear from our data what may be causing the imbalance between male and female users when the US Census lists New York City as having more females (52.3%). It is possible that the citibike program has been marketed more to males or perhaps female attire in the city is less conducive to bikes. Further investigation would be needed to determine the cause.


#### Trip/Ride Durations
![Image of Trip/Ride Durations by Customer Types](https://github.com/ozloty06/Tableau_CitiBike/blob/main/Trip_Durations.png)
Citibike customers in New York City are most likely to share a bike for a trip lasting less than 30 minutes. Less than 1000 trips lasted exactly one hour in August while almost 150,000 trips were only 5 minutes long. It is likely that this is because the bikes are an incredibly effective means of commuting in New York City where destinations are relatively close to each other, and potentially close to starting/stopping locations where the bike share operates. 


![Image of Trip/Ride Durations by Gender](https://github.com/ozloty06/Tableau_CitiBike/blob/main/Checkout_byGenders.png)
Total trip length (time bikes are checked out) is often shorter than 30 minutes across all genders. Both males and females follow similar patterns of trip duration, peaking at 5-7 minutes and dropping off dramatically after 20 minutes. Interestingly, the pattern for users of unknown gender is slightly different where trip duration ranges from 5 to 25 minutes evenly without a peak. Like males and females, however, trip duration is unlikely to exceed 1 hour.


#### Daily Usage 
![Image of Trips/Rides by Day](https://github.com/ozloty06/Tableau_CitiBike/blob/main/Trips_by_Day.png)
When we review daily use patterns, a pattern quickly emerges for citibike in New York City. Weekday usage tends to concentrate on morning and afternoon commute times, between 7am-10am and 4pm-8pm. Strangely, on Wednesday this pattern is less pronounced for the evening commute. Thursdays, meanwhile, appear to be the most popular days to commute by bike share. 

Weekend days, on the other hand, indicate a much more distributed use of the bike sharing by users with an even distribution between 10am-8pm with slightly increased usage between 11am and 5pm. 


![Image of Trips/Rides by Customer Type by Day](https://github.com/ozloty06/Tableau_CitiBike/blob/main/Trips_by_Customer.png)
Our graphing of daily usage by customer segment and gender clearly indicates that male subscribers who are most likely to use the bike share program on weekdays are the most active users of citibike. While subscription females are less likely to use bike sharing than their male counterparts, their use patterns are very similar over the course of the week. Most customers without a subscription are likely to use bike sharing evenly across all days of the week with a very slight preference for weekend use.

While the people of unknown gender seem most likely to be customers without a subscription, it is likely that non-subscribing customers are less likely to provide demographic data, such as gender, which could account for what we see when we compare customers to subscribers. 


### Summary
A complete presentation of the above analysis can be found [here](https://public.tableau.com/app/profile/maggie6503/viz/Tableau_CitiBike-Analysis/Story1?publish=yes).

Based on the results of our analysis, our Des Moines, Iowa, bike share program may benefit from considering initially targetting male weekday commuters and weekend riders of all genders throughout the day. Further, it is likely that most riders would want to be able to find a stop location to return bikes within a 20 minute ride from their starting location and possibly closer to 5 minutes apart in the downtown areas of Des Moines. A subscription program is ideal to ensure a regular and dependable stream of revenue to support bike maintenance and operational costs.

Before the Des Moines bike share program can launch, it would be beneficial to further study the citibike program to understand:
- age distribution of customers and subscribers to ensure a comparable market of the right size exists in our midwest city.
- subscription data to better understand the price point, length of membership, appetite for tiered subscriptions, usage patterns by subscription type, etc.
- non-customer data to provide insight into operational costs, including bike repair and maintenance, life cycle of bike equipment, liability exposures, shrinkage and theft issues, etc.
