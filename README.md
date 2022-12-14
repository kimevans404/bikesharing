# bikesharing

## Overview of the analysis
A proposal has been made to start a bike-sharing program in Des Moines, and an analysis of bike-sharing in New York City will be used to show investors that it is a solid business proposal. The NYC bike-sharing data was pulled from [this website](https://ride.citibikenyc.com/system-data) made available by citibike, and the analysis was performed with Tableau.
The Tableau Story for this analysis can be viewed [here.](https://public.tableau.com/app/profile/kimber.evans/viz/Bikesharing_Challenge_16705526505010/Story1)

## Results
Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image.

Using only one month of data there is a very clear picture showing the success of this program. 

### Trips and Usertype
<img width="570" alt="1_TripsAndUsertype" src="https://user-images.githubusercontent.com/111471057/206912560-cce2abda-e1d1-476d-b9c6-01769a918c51.png">
In this visualization we can see that there were 2,344,224 trips in August 2019 in New York City. 80% of those trips were made by users with subscriptions which shows that 1 out of every 5 rides is a user who hasn't subscribed. The gender of users is 65% male and 25% female with 10% unknown. Going forward we will review total usage and usage by gender. 


### Trip Duration
<img width="1035" alt="2_TripDuration" src="https://user-images.githubusercontent.com/111471057/206912549-2644c180-046a-44db-97cd-3f78caf56479.png">
It is most common for bike trips to be less than one hour, and the majority of those trips are less than 10 minutes. There is some data (not shown) where trips may last over 2 hours (less than 100 trips per minute), and also some usage (less than 50 users) was between 23 and 24 hours.

### Trip Duration by Gender
<img width="1128" alt="3_TripDurationGender" src="https://user-images.githubusercontent.com/111471057/206912579-015ea630-cdc9-4487-b67e-c3ca1d6e68ac.png">
Here we can see the breakdown of trip duration by a user's gender. Knowing that 65% of usage in the month was male explains why the spike on the graph nearly matches the overall trip duration from the previous visualization, but we can see a very similar drop off of time used for females as well. 

### Total Usage by Time and Weekday
<img width="712" alt="4_Weekday" src="https://user-images.githubusercontent.com/111471057/206912593-006c922b-8088-47f5-b50f-c0fac02c6e19.png">
This visualisation shows that bike usage mimicks vehicle usage. There are more bikes being used during traditional rush hour times, as well as higher usage during the day on Saturdays. There is significantly less use Wednesday evenings. The reason behind this is not in the data, and is possibly specific to transit pricing or availability in NYC on Wednesdays.

### Weekday Usage by Gender
<img width="1483" alt="5_WeekdayGender" src="https://user-images.githubusercontent.com/111471057/206912624-78a456b0-ba84-4920-8aa9-5e7b1e97a434.png">
Reviewing the same time and weekday usage split by gender we can see the pattern of rush hour usage is mirrored with male and female users. There is a slightly different pattern for the users of unknown gender; the usage is higher on weekends. 

### Weekday Usage by Gender and Customer Type
<img width="638" alt="6_WeekdayCustomer" src="https://user-images.githubusercontent.com/111471057/206912651-3a42f420-448f-4f81-bc70-bdaf0e59458e.png">
In this visualization it is clear now that the users of unknown gender are not subscriptions users. It is most likely that these users are tourists or visitors and only need use of the bikes on the weekend. Because subscribers use the bikes less on the weekend, the customers help to keep the usage up.

## Summary
This analysis shows that bike usage is in high demand every day of the week, and the bike sharing program benefits locals and vistors. Further analysis could be performed on the provided data to show a heatmap for age and gender of subscribers to get a better idea of who repeat customers are. Additionally, a visualization could be made for the location of bike stations and well as the total number that is supporting the program.

[Link to Tableau Public Story](https://public.tableau.com/app/profile/kimber.evans/viz/Bikesharing_Challenge_16705526505010/Story1)
