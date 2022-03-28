# Bikesharing
## Overview
This analysis is intended to supplement conversations surrounding the expansion of bikesharing programs to Des Moines, IA. To accomplish this, visualizations have been constructed in Tableau.

## Results
### User Types
Approximately 1 in 5 rides are had by customers, leaving a little more than 4 in 5 rides that are used by subscribers.

![User Types Pie Chart](https://github.com/kramerkyle/bikesharing/blob/48c55171e61b4bf4d1ae600636adab92c81b6ffe/User%20Types.png)

### Start Locations
The most popular starting locations are on the Lower West Side of the island. This is a popular place for young professionals to live and work, which is consistent with the demographic that is likely the strongest user base.

![Start Locations Map](https://github.com/kramerkyle/bikesharing/blob/48c55171e61b4bf4d1ae600636adab92c81b6ffe/Start%20Locations.png)

### Ride Durations
It's important to note the ride durations to better understand how users are interacting with the bike sharing. In aggregate, it is clear that almost all rides endure for less than one hour.

![Total Checkout Durations](https://github.com/kramerkyle/bikesharing/blob/48c55171e61b4bf4d1ae600636adab92c81b6ffe/Checkout%20Duration%20for%20Users.png)

The above findings hold true when breaking out by gender: most rides last less than 30 minutes. Men seem to be more likely to take rides and compose a greater percentage of ridership at each point in time.

![Ride Duration by Gender](https://github.com/kramerkyle/bikesharing/blob/48c55171e61b4bf4d1ae600636adab92c81b6ffe/Ride%20Duration%20by%20Gender.png)

### Trips
Understanding the breakdown of user type, checkout duration, and gender is informative. However, we can also look at when the rides occur during the week. Looking at it by weekday and hour, rides occur most outside of 10-4 Monday through Friday.

![Trips by Weekday & Hour](https://github.com/kramerkyle/bikesharing/blob/48c55171e61b4bf4d1ae600636adab92c81b6ffe/Trips%20by%20Weekday%20%2B%20Hour.png)

Breaking this down by gender depicts darker contrast within MALE users, but this is due to the surplus of male users.

![Trips by Weekday, Hour, Gender](https://github.com/kramerkyle/bikesharing/blob/48c55171e61b4bf4d1ae600636adab92c81b6ffe/Trips%20by%20Weekday%2C%20Hour%2C%20Gender.png)

Breaking this down by Trips by Weekday & Gender shows that customers are most likely to attempt bikesharing on the weekends. Subscribers' most happening days are Thursday and Friday.

![Trips by Weekday & Gender](https://github.com/kramerkyle/bikesharing/blob/48c55171e61b4bf4d1ae600636adab92c81b6ffe/Trips%20by%20Weekday%20%2B%20Gender.png)

## Summary
### Additional Visualizations
Additional visualizations could be helpful to depict the data in new and exciting ways. One would be the sum of trip duration affecting the size and the count of trips impacting the color of Bike IDs. 

The second visualization that would be helpful would aim to visualize the number of bikes that are returned more than 2 miles from where they were rented. This would require a series of calculated columns to calculate maximum and minimum variations in longitude and latitude. If this trip passes the 2 mile mark, then it would have a flag. The count of flags should be set as the color on the starting station.

### Final Results Summary
In conclusion, men and subscribers are the most avid users of the bike sharing program. Most rides occur just before and after work. Thursdays and Fridays after work are the most popular, followed by Saturday and Sunday. Interactive visualizations can be found at this [link to dashboard](https://public.tableau.com/app/profile/kyle.kramer2933/viz/Bikesharing_16484026008570/NYCBikeshare?publish=yes).
