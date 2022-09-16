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
URL to this graph in Tableau (https://public.tableau.com/app/profile/digamber.rane/viz/NYC-BikeShare-Challenge/CheckouttimeAllUsers) 

![Checkout time All Users](https://user-images.githubusercontent.com/107159218/190541981-3b9ed79a-57fb-4aac-b81f-b254c2b0720e.png)

2. Line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender
URL to this graph in Tableau (https://public.tableau.com/app/profile/digamber.rane/viz/NYC-BikeShare-Challenge-CheckouttimebyGender/CheckoutTimesbyGender)

![Checkout Times by Gender](https://user-images.githubusercontent.com/107159218/190542310-884a3abd-7a05-4c4c-ab62-0b0fea43e988.png)

3. A heatmap is created showing the number of bike trips for each hour of each day of the week 
URL to this graph on Tableau (https://public.tableau.com/app/profile/digamber.rane/viz/NYC-BikeShare-Challenge-TripsbyWeekdayHour/TripsbyWeekdayHour)

![Trips by Weekday_Hour](https://user-images.githubusercontent.com/107159218/190542460-dea265b9-2dac-41ee-8483-e807daee8309.png)

4. A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender
URL to this graph on Tableau (https://public.tableau.com/app/profile/digamber.rane/viz/NYC-BikeShare-Challenge-TripsbyGender/TripsbyGender)

![Trips by Gender](https://user-images.githubusercontent.com/107159218/190542662-8e86262a-589f-4ce5-ac71-126db9e2ad94.png)

5. A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender
URL to this graph on Tableau (https://public.tableau.com/app/profile/digamber.rane/viz/NYC-BikeShare-Challenge-UserTripsbyGenderbyWeekday/UserTripsbyGenderbyWeekday) 

![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/107159218/190542772-a4384468-3f54-4df0-957f-765e00c99ac1.png)

For both the analysis the![Uploading User Trips by Gender by Weekday.png…]()
 only major challenge was my unfamiliarity with excel functions. For the first analysis generating pivot tables and charts was fairly straight forward. One issue that I face was when filtered using the newly created "Years" column. I would not see months and I had to use the "Date ended conversion" column instead as it breaks down into quaters and months.

For the second analysis, my only complain would be typing the Goals column. I am sure that one could write a script to fill in this column, especially if there were more entries in this column than the 12 listed.

## Result

### Theater Outcome Based on Launch Date

The two conclusions that can be drawn from this analysis are;
1. Months May-July are most favorable to start a crowdfunding project. The success to fail ratio for these three months are quite similar (65%+/-2) and eventhough May would look the better month June would be not a distant second choice.
2. Setting up a crowdfunding project should be avoided in the month of December as there's a equal chance that it may fail. 

### Outcome Based on Goals

The clear conclusion here is not to set a crowdfunding goal between $45,000-$49,999 as it has a 100% chance of failure. 

## Limitation

1. One limitation is that this data is not current and relies on information collected between 2010-2017. To get a more realistic picture data generate from 2015-current should be considered.
