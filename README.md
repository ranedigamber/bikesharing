# Citibike

# Overview of the Project

The goal of this project is to create a visualiation for a proposal to seek investor funding for a bike sharing program for the city of Des Moines. This would be based on data obtained from a bike sharing program based in New York City.
We will be using Jupyter notebook to reformat a column in the original csv flat file and use Tableau to render the visualization.

## Analysis of the Challenge
### Data clean up and formatting

We used Jupyter notebook and Pandas to modify the tripduration field in this csv file from integer to a new field named "new_tripduration" in datetime format. 
Here's the data type description before the transformation. 

![Bikesharing_dtype_initial](https://user-images.githubusercontent.com/107159218/190541276-ceee254e-363f-422a-a2f8-690a3644cf07.PNG)

Here's the data type description after transforamtion including a new field (new_tripduration) in the datetime format

![Bikesharing_dtype_transformed](https://user-images.githubusercontent.com/107159218/190541431-4d3eb450-c202-41bf-b5ec-84fb7c557bae.PNG)

### Challenges

For both the analysis the only major challenge was my unfamiliarity with excel functions. For the first analysis generating pivot tables and charts was fairly straight forward. One issue that I face was when filtered using the newly created "Years" column. I would not see months and I had to use the "Date ended conversion" column instead as it breaks down into quaters and months.

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
