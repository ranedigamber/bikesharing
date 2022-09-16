# Citibike

# Overview of the Project

The goal of this project is to create a visualiation for a proposal to seek investor funding for a bike sharing program for the city of Des Moines. This would be based on data obtained from a bike sharing program based in New York City.
We will be using Jupyter notebook to reformat a column in the original csv flat file and use Tableau to render the visualization.

## Analysis of the Challenge
### Data clean up and formatting (Deliverable 1.)

We used Jupyter notebook and Pandas to modify the tripduration field in this csv file from integer to a new field named "new_tripduration" in datetime format. 
Here's the data type description before the transformation. 

![Bikesharing_dtype_initial](https://user-images.githubusercontent.com/107159218/190541276-ceee254e-363f-422a-a2f8-690a3644cf07.PNG)

Here's the data type description after transforamtion including a new field (new_tripduration) in the datetime format

![Bikesharing_dtype_transformed](https://user-images.githubusercontent.com/107159218/190541431-4d3eb450-c202-41bf-b5ec-84fb7c557bae.PNG)

### Analysis and Visualization in Tableau

### Deliverable 2.
1. Line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.

**The usage reached to a max of 3000 min per user**

URL to this graph in Tableau (https://public.tableau.com/app/profile/digamber.rane/viz/NYC-BikeShare-Challenge/CheckouttimeAllUsers) 

![Checkout time All Users](https://user-images.githubusercontent.com/107159218/190541981-3b9ed79a-57fb-4aac-b81f-b254c2b0720e.png)



2. Line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.

**Male generally have a higher usage of this service over other genders**

URL to this graph in Tableau (https://public.tableau.com/app/profile/digamber.rane/viz/NYC-BikeShare-Challenge-CheckouttimebyGender/CheckoutTimesbyGender)

![Checkout Times by Gender](https://user-images.githubusercontent.com/107159218/190542310-884a3abd-7a05-4c4c-ab62-0b0fea43e988.png)



3. A heatmap is created showing the number of bike trips for each hour of each day of the week.

**Morning 6-10 and evening 4-8 seem like the peak hours of usage of this service**

URL to this graph on Tableau (https://public.tableau.com/app/profile/digamber.rane/viz/NYC-BikeShare-Challenge-TripsbyWeekdayHour/TripsbyWeekdayHour)

![Trips by Weekday_Hour](https://user-images.githubusercontent.com/107159218/190542460-dea265b9-2dac-41ee-8483-e807daee8309.png)



4. A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.

**Males are the highest users of this service during the peak hours**

URL to this graph on Tableau (https://public.tableau.com/app/profile/digamber.rane/viz/NYC-BikeShare-Challenge-TripsbyGender/TripsbyGender)

![Trips by Gender](https://user-images.githubusercontent.com/107159218/190542662-8e86262a-589f-4ce5-ac71-126db9e2ad94.png)



5. A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender.

**Males tend to be the largest users of this service**

URL to this graph on Tableau (https://public.tableau.com/app/profile/digamber.rane/viz/NYC-BikeShare-Challenge-UserTripsbyGenderbyWeekday/UserTripsbyGenderbyWeekday) 

![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/107159218/190542772-a4384468-3f54-4df0-957f-765e00c99ac1.png)



6. Additional analysis and visualization from the modules (Compilation of total number of users)

**More that 85% of users of this service are subscribers**

URL to this graph on Tableau (https://public.tableau.com/app/profile/digamber.rane/viz/NYC-BikeShare-ModulesUsers/NYC-BikeRideShare-Users)

![NYC-BikeRideShare-Users](https://user-images.githubusercontent.com/107159218/190543253-941d7084-bd12-4064-9247-6356cb030335.png)



7. Additional analysis and visualization from the modules (Compilation of users by gender type)

**More that 80% of users are males**

URL to this graph on Tableau (https://public.tableau.com/app/profile/digamber.rane/viz/NYC-BikeShare-ModulesGenderBreakdown/GenderBreakdown)

![Gender Breakdown](https://user-images.githubusercontent.com/107159218/190543441-2d34b787-6094-412a-a1eb-acd68338ef1b.png)


## Summary
Based on the analysis of the data from NYC provided the following observations can be summarized;
1. Bike maintainence can be best done between the hours of 1-5 as there is a less demand for the ridesharing during these times of the day.
2. Males a by far the biggest users of this service
3. During weekdays hours 6-9 and 4-7 sees the highest usage and demand of this service in both genders. Males tend to be users of this service even on weekend from 7-5

