# Pyber_Analysis

### Background
Create an overall snapshot of the ride-sharing data and a summary table of key metrics of the ride-sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type.

### Objectives:

1. Use Pandas functions like groupby, pivot, resample, and reset_index on a DataFrame.
2. Use Pandas methods and attributes on a DataFrame or Series.
3. Create a new DataFrame from multiple groupby() Series.
4. Format columns of a DataFrame.
5. Create a multiple-line graph.
6. Annotate and apply styling to the chart.
7. Part 1 Instructions
8. Create a PyBer Summary DataFrame
9. Create a summary DataFrame that showcases the total riders, total drivers, total fares, average fare per ride, and average fare per driver for each city type

### Instruction

1. Get the total rides, total drivers, and total fares for each city type using the groupby() function on the city type using the merged DataFrame or separate DataFrames.
2. Calculate the average fare per ride and the average fare per driver by city type.
3. Delete the index name.
4. Create the summary DataFrame with the appropriate columns and apply formatting where appropriate.

### Finding

The summary Dataframe shows an overview of fare and rides in the three city types: urber, suburban and rural.
#### According to the data rural cities have:
- The highest fare per ride
- The highest fare per driver
- The total fare, total drivers and total rides are the lowest numbers.
#### According to the data urban cities have:
- The lowest fare per ride
- The lowest fare per driver
- The total fare, total drivers and total rides are the highest numbers.
We can conclude that urban cities have cheaper fares with high number of drivers and rides.

#### Final Summary Table

![dataframe](https://github.com/Kalkidanalemaye/Pyber_Analysis/blob/master/summarytable.jpg)

## Multiple-Line Plot for the Sum of the Fares for Each City Type
According to the plot, urban cities have the highest fares and all cities have a high peak just before the month of March.
Sururban cities have lower fares compared to urban cities but higher fares compared to rural cities which have the lowest fares.
