# bikesharing
## Overview
An analysis of New York City's bikeshare company, Citibike, was performed with the idea of bringing a similar bikeshare program to Demoins Island. Specifically, this analysis looks at the gender breakdown, trip duration, and weekly usage of Citibike's customers. 

[link to dashboard](https://public.tableau.com/app/profile/jennifer.klein6089/viz/citi-bikesharingNU/Story1)

## Resources
* Python / Pandas
* Tableau

## Results
### Checkout times for Different Users

This graph is confusing, and I'm not sure adds to the analysis. If 0 is 12am, then the most users checkout bikes at 12:10, and that's inconsistent with the other heatmaps. Suggest removing to avoid confusion. Same applies to Checkout Times by Gender graph. 

### Gender Breakdown

Males make up over half of Citibike's customer base, followed by females, which make up roughly a quarter, and the remainder are unknown. 

### AVG Trip by Gender 

The average trip duration is highest for the unknown gender at 2,200 seconds (36.7 mins). Females and males have similar average trip durations at 1,064 seconds (17.7 mins), and 873 seconds (14.55mins) respectively. 

### Checkout Times by Gender
Males have the highest number of bikes checked out at over 100k rides in the first 10 mins. Women are just above 33k number of rides checked out. 

### Trips by Weekday per Hour
Citibike sees the highest usage on weekdays 7-9AM and 5-7pm, and on Saturdays 10am-6pm. Thursdays between 7-9pm are the absolute highest usage times during the week. Monday-Friday 1-4am are the lowest usage times of the week. 

### Trips by Gender
Building off the previous graph, this graph shows that of all three gender categories, males used the citibikes the most and they used them the most during peak hours of weekdays 7-9am and 5-7pm. The unknown gender used the citibikes the most infrequently. 

### User Trips by Gender by Weekday
Males make up a high quantity of the citibike subscribers, and use citibikes in higher frequency on Thursdays and Fridays compared to other days of the week. Unknown genders make up the lowest number of Citibike subscribers. The Citibike customers(non-subscribers) are an even mix of males, females and unknown genders. 

### Usage by Gender Breakdown
This dashboard is an amalgamation of the gender vizulations noted above. 


## Summary

Males make up the highest proportion of citibike subscribers, so it is unsurprising that they use the bikes the most overall and during peak hours. Interestingly though, females have higher average trip duration. It would be interesting to create a vizualization with both the start stations and end stations to determine which stations are the highest use. As well, the birth year could be plotted with the bikeid and the genders could be colour markers - this would give a better idea of the target demographic Demoins Island can target. As well, the genders could be plotted in to box plots to determine the outliers and consider those that may be skewing the data. 

