# Explore-Weather-Trends-using-R

Explore Weather Trends project. I have explored the weather data for Bangalore for the past 200 years and made a comparison to Global weather patterns and reported my findings

# Exploring Weather Trends - Project Instructions

## Summary
In this project, you will analyze local and global temperature data and compare the temperature trends where you live to overall global temperature trends.

## Instructions
Your goal will be to create a visualization and prepare a write up describing the similarities and differences between global temperature trends and temperature trends in the closest big city to where you live. To do this, you’ll follow the steps below:
1. Extract the data from the database. There's a workspace that is connected to a database. You’ll need to export the temperature data for the world as well as for the closest big city to where you live. You can find a list of cities and countries in the city_list table. To interact with the database, you'll need to write a SQL query.

>#### Extracting the Data
>Use the SQL Workspace to extract data from the temperatures database, then download the results to a CSV. Then you can open it up in a spreadsheet program in order to analyze it.
>##### The Database Schema
>There are three tables in the database:
>- city_list - This contains a list of cities and countries in the database. Look through them in order to find the city nearest to you.
>- city_data - This contains the average temperatures for each city by year (ºC).
>- global_data - This contains the average global temperatures by year (ºC).

2. Write a SQL query to extract the city level data. Export to CSV.
3. Write a SQL query to extract the global data. Export to CSV.
4. Open up the CSV in whatever tool you feel most comfortable using. We suggest using Excel or Google sheets, but you are welcome to use another tool, such as Python or R.
5. Create a line chart that compares your city’s temperatures with the global temperatures. Make sure to plot the moving average rather than the yearly averages in order to smooth out the lines, making trends more observable (the last concept in the previous lesson goes over how to do this in a spreadsheet).
6. Make observations about the similarities and differences between the world averages and your city’s averages, as well as overall trends. Here are some questions to get you started.
7. Is your city hotter or cooler on average compared to the global average? Has the difference been consistent over time?
8. “How do the changes in your city’s temperatures over time compare to the changes in the global average?”
9. What does the overall trend look like? Is the world getting hotter or cooler? Has the trend been consistent over the last few hundred years?

