# Citibike Analysis
## Purpose
This is an analysis of data from Citibike program in New York in August of 2019. We used this data to understand trends that could be applied to a potential business opportunity with Citibike in Des Moines. 
## Visualizations
Tableau Dashboard: https://public.tableau.com/app/profile/samantha.wright4448/viz/Citbike_Story/RidershipData
Data Source: [Citi Bike System Data | Citi Bike NYC](https://www.citibikenyc.com/system-data)

## Overview of Analysis
Pandas was used to convert the "tripduration" column in the dataset from an integer to a datetime datatype. 
![citibike](https://user-images.githubusercontent.com/79758494/122776091-65249b00-d270-11eb-814d-b78e2b6debb5.PNG)

After completing this task, Tableau was used to analyze the data and to create visualizations to show to stakeholders in order to strengthen the proposal for a Citibike program in Des Moines. 

#### Trip Duration

First, the checkout times were analyzed.
![Checkout_Times](https://user-images.githubusercontent.com/79758494/122777533-bda86800-d271-11eb-9f5d-1b7b9aabe340.PNG) 

Then, we looked at checkout times by gender. 
![Checkout_Times_by_Gender](https://user-images.githubusercontent.com/79758494/122777535-bda86800-d271-11eb-85aa-81fbf7800a0a.PNG)

Both of these visualizations show that "tripduration" typically lasts less than an hour, with the "peak" trip duration being around 5 minutes for males, 6 minutes for females, and 10 minutes for "unknown."

#### Checkout Times
![Weekday_trips](https://user-images.githubusercontent.com/79758494/122777490-b4b79680-d271-11eb-831d-9471450c60c8.PNG)

Then, the checkout times per weekday were looked at to determine the highest volume per hour, per day. 

![Trips_by_gender](https://user-images.githubusercontent.com/79758494/122777492-b4b79680-d271-11eb-91d4-ff3d09407c37.PNG)

Then, looking at the checkout times per week, we also looked at the checkout times by gender. 

![usertype_gender](https://user-images.githubusercontent.com/79758494/122777489-b4b79680-d271-11eb-8e83-3bee8ba2f0d7.PNG)

Finally, we looked at checkout times, user types  and gender. 

What these three visualizations show is that Males have the highest number of checkouts over females and "unknown." It also shows that between the hours of 7am-9am and 5pm-7pm, there is a higher level of checkout volume. It also shows that weekdays (Monday-Friday) have more checkout volume than on the weekends. 

#### Demographics
Visualizations for Demographics were then created. 

![ridership_data](https://user-images.githubusercontent.com/79758494/122777514-b97c4a80-d271-11eb-8850-3d7083a020b9.PNG)

A bar graph was also created to show, again, checkout time volume. 
![ridership_data2](https://user-images.githubusercontent.com/79758494/122777509-b97c4a80-d271-11eb-9645-6c4414c1b099.PNG)


## Summary
This data shows that males are more likely to participate in Citibike ridership. This data also shows that the times with the highest volumes in ridership are Monday thru Friday 7am-9am and 5pm-7pm. I think with this data, one might be able to summarize that the times with the highest volume are also times in which the workday begins and ends for many. This shows that the majority of Citibike volume comes from transportation needs to and from work. 

There are two addition visualizations that may help in the future. First, looking at the checkout times, age and gender to determine the average age of those using Citibike. Second, looking at checkout times station start and end, and trip duration. 