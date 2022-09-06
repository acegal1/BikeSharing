# Citibike Analysis

Citi Bike is the nation's largest bike sharing program, with 25,000 bikes and over 1,500 stations across Manhattan, Brooklyn, Queens, the Bronx, Jersey City and Hoboken.  Can it be replicated successfully?


# Overview of the statistical analysis:

The purpose of the current analysis is to show potential investors using visualizations that the successful NYC Citibike bike-sharing program can be implemented in Des Moines. The visualizations below show:

 1) The length of time that bikes are checked out for all riders and genders,

 2) The number of bike trips for all riders and genders for each hour of each day of the week

 3) The number of bike trips for each type of user and gender for each day of the week.

# Resources:

Software: Tableau, Python, Jupyter NoteBook and Pandas Library
Source Files: 201908-citibike-tripdata.csv, 201908-citibike-revised_tripdata.csv

# Results:

### Link of final Analysis : [Story of bikesharing By Connie Aceves](https://public.tableau.com/app/profile/connie.aceves.acegal1./viz/Citibike_16624110419330/NewYork_Citibike)

1. Looking at visualizations for 'Checkout Times for Users' and 'Checkout Times by Gender', we see that most rides are for 30 minutes or less. Regardless of gender. Note that utilization period is in direct correlation of fee amounts charged by minutes.

![Checkout times for users](https://github.com/acegal1/BikeSharing/blob/main/images/checkout_user.jpg)


2. Total numbers 'Checkout times by Gender' the data shows "MALE" riders and duration of rides less than 30 minutes.  We also see that this pattern is the same regardless of gender.

![Checkout times by gender](https://github.com/acegal1/BikeSharing/blob/main/images/checkout_gender.jpg)

3. The heatmap of 'Trips by Weekday per Hour' shows a clear pattern of bicycle useage 1) during the morning weekday commute (7-9 a.m.), 2) during the evening weekday commute (4-7 p.m.) except on Wednesday evenings, and 3) all day long on weekends.

![bike share during weekday](https://github.com/acegal1/BikeSharing/blob/main/images/weekday.jpg)

4. Although useage as per 'Trips by Gender(Weekday per Hour)' is significantly higher among Males, the pattern of hours where bikes are nost-used is the same regardless of gender.

![bike sharing by gender](https://github.com/acegal1/BikeSharing/blob/main/images/gender.jpg)

5. 'User Trips by Gender by Weekday' The Customers check bikes more often during weekends whereas Subcribers checkout bikes during Weekdays.
 
   Amongst Subscribers the Most busiest day is Thursday whereas the least busiest day is Sunday.

 
   ![usertrip by gender by weekday](https://github.com/acegal1/BikeSharing/blob/main/images/usertrip_gender.jpg)
 
 6. Comparing visualizations for the 'Top Starting Locations' and 'Top Ending Locations', we can see that the most active starting locations are also among the most active ending locations.
 
    The most popular places for Citibike customers to begin their journeys in New York City are:   Pershing Square North and  Broadway
    
   
    
 ![Top starting location(with station name)](https://github.com/acegal1/BikeSharing/blob/main/images/topstart.jpg)
 
 7. The most popular places for Citibike customers to end their journeys in New York City are the same as starting locations: Pershing Square North and Broadway
 
 ![Top Laction(with station name)](https://github.com/acegal1/BikeSharing/blob/main/images/endtop.jpg)
 
 
 # Summary:
 
The analysis of the utilization of bicycles in the NYC Citibike bike-sharing program does show patterns of usesage by time and by gender.  You can see utilization rates can now be predicted based on time of day and location. As well as weekday useage has been concentrated around the morning and afternoon commute. While weekend useage is more evenly spread through the day. 
 
Would recommend further analysis of single rides for weekend versus weekday trips.  Citi Bike limits bike rides to 30 minutes and anything past that is .39 cents per minute. Would recommend futher analysis to compare trip durations past 30 minutes. Additional visualization that could be created would be of bicycles in specific locations that are not used. 

However, can the bike share program be replicated successfully for the city of Des Moines?  No, New York in 2018 had 65.8 million tourist that visited and eventhough the city of Des Moines is the capital of Iowa, tourism numbers for the year of 2019 was 269,479. 

