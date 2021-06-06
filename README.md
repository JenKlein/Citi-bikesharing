# bikesharing
## Overview
An analysis of New York City's bikeshare company, Citibike, was performed with the idea of bringing a similar bikeshare program to Demoins Island. Specifically, this analysis looks at the gender breakdown, trip duration, and weekly usage of Citibike's customers. 

[link to dashboard](https://public.tableau.com/app/profile/jennifer.klein6089/viz/citi-bikesharingNU/Story1)

## Resources
* Python / Pandas
* Tableau

## Results
### Checkout times for Different Users

<img width="894" alt="Screen Shot 2021-06-06 at 6 08 46 PM" src="https://user-images.githubusercontent.com/69849998/120941728-3f38bb80-c6f2-11eb-832b-51001a8fe08a.png">

### Gender Breakdown

<img width="205" alt="Screen Shot 2021-06-06 at 6 09 12 PM" src="https://user-images.githubusercontent.com/69849998/120941735-4f509b00-c6f2-11eb-874e-3e43a3c4ffbb.png">

Males make up over half of Citibike's customer base, followed by females, which make up roughly a quarter, and the remainder are unknown. 

### AVG Trip by Gender 

<img width="303" alt="Screen Shot 2021-06-06 at 6 09 42 PM" src="https://user-images.githubusercontent.com/69849998/120941740-60011100-c6f2-11eb-91c6-0d73dd0e5d61.png">

The average trip duration is highest for the unknown gender at 2,200 seconds (36.7 mins). Females and males have similar average trip durations at 1,064 seconds (17.7 mins), and 873 seconds (14.55mins) respectively. 

### Checkout Times by Gender

<img width="1055" alt="Screen Shot 2021-06-06 at 6 10 28 PM" src="https://user-images.githubusercontent.com/69849998/120941753-7ad38580-c6f2-11eb-8d36-810b07665174.png">

Males have the highest number of bikes checked out at over 100k rides in the first 10 mins. Women are just above 33k number of rides checked out. 

### Trips by Weekday per Hour

<img width="525" alt="Screen Shot 2021-06-06 at 6 11 09 PM" src="https://user-images.githubusercontent.com/69849998/120941777-9343a000-c6f2-11eb-9acf-257e9a6633a9.png">

Citibike sees the highest usage on weekdays 7-9AM and 5-7pm, and on Saturdays 10am-6pm. Thursdays between 7-9pm are the absolute highest usage times during the week. Monday-Friday 1-4am are the lowest usage times of the week. 

### Trips by Gender

![Screen Shot 2021-06-06 at 6 12 28 PM](https://user-images.githubusercontent.com/69849998/120941801-c2f2a800-c6f2-11eb-9aca-4478c3ef2011.png)

Building off the previous graph, this graph shows that of all three gender categories, males used the citibikes the most and they used them the most during peak hours of weekdays 7-9am and 5-7pm. The unknown gender used the citibikes the most infrequently. 

### User Trips by Gender by Weekday

![Screen Shot 2021-06-06 at 6 12 54 PM](https://user-images.githubusercontent.com/69849998/120941811-d271f100-c6f2-11eb-98ce-c2ebdc3aefeb.png)

Males make up a high quantity of the citibike subscribers, and use citibikes in higher frequency on Thursdays and Fridays compared to other days of the week. Unknown genders make up the lowest number of Citibike subscribers. The Citibike customers(non-subscribers) are an even mix of males, females and unknown genders. 

### Usage by Gender Breakdown
This dashboard is an amalgamation of the gender vizulations noted above. 


## Summary

Males make up the highest proportion of citibike subscribers, so it is unsurprising that they use the bikes the most overall and during peak hours. Interestingly though, females have higher average trip duration. It would be interesting to create a vizualization with both the start stations and end stations against the trip duration to determine which stations have the highest use. As well, the birth year could be plotted with the bikeid and the genders could be colour markers - this would give a better idea of the target demographic Demoins Island can target. As well, the genders could be plotted in to box plots to determine the outliers and consider those that may be skewing the data. 

