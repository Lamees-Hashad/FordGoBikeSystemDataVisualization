# Ford GoBike System Data
## by Lamees Mahmoud


## Dataset

> This dataset includes information about 2407838 individual rides made in a bike-sharing system covering the greater San Francisco Bay area during 2019. In this analysis we focus on the these features: Trip Duration, Start Time and Date, User Type. Rows that include Null or missing values are dropped also the unused columns are dropped. The Start Time and Date column is split to 3 columns timeOfDay, dayOfWeek and month. The duration column is converted from sec to min. A subdataframe is created to hold the top routes and their coordinates.

## Summary of Findings

> - The time of day with the most trips taken is the afternoon.
> - The days of the week with the most trips are the weekdays, and the days of the week with the least trips are the weekends.
> - The month with the most trips are March, April and Octoper and the month with the least trips is December.
> - The average trip duration is around 10 minutes.
> - Subscribers represent a larger percentage (more than 75%) of the total users than the customers.
> - The top used start stations and top used end stations are mostly the same, also the top routes mostly consists of these top stations as expected. The top 10000 routes are clustered in 3 groups.
> - The median of the ride duration is around 10 minutes across the different times.
> - The median of the ride duration for customers is longer than for subscribers.
> - The number of customers is highest in the afternoon, doesn't change much with the days of the week and highest in December.
> - The longest rides are in the weekend aftenoons during spring till midsummer and the shortest rides are in december.
> - customers' ride duration averages are always longer than subscribers.
> - subscribers' ride duration averages vary slightly around 10 minutes, while customers' ride duration averages vary in a longer range.

## Key Insights for Presentation

> - when analyzed separately, the user types average durations vary differently across the different times.
> - user types affect the ride durations across the different times.
> - subscribers probably use the bikes to get to places (instead of cars) and for daily exercise, while customers could be tourist visiting San Francisco Bay area for spring or summer and using the bikes for fun or they could be people using the bikes from time to time but not regularly.
> - to gain more insight of why customers' rides are longer than subscribers' rides I think we need to collect more data about the users, this would help the company to maybe create more types of subscribtions that would suite a more of people.
