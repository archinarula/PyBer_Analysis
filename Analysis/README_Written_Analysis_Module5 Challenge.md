# Written Analysis of the PyBer Ride Sharing Data Analysis

## Overview of Analysis
This project is about analysis of all the rideshare data from Jan-May 2019 to tell a compelling story about the variations by city types. The total drivers, total rides ,total fares and average fare per ride were obtained using the groupby function, while the average fare per driver was obtained by dividing the total fares per city type by the total drivers per city type. Datetime index function was used to set datatype of index and a pivot tabel was created. Loc function was used to organize the pivot table which was then resampled and finally matplotlib was used to visually represent the trend by creating line charts per city type.

### Purpose
The purpose of this ride sharing data analysis is to identify key ride sharing metrics by type of city and create a graphical representation of the total weekly fares based on the city types which will help PyBer improve access to ride sharing services and determine ride affordability.

#### Deliverable: This analysis and code consists of a technical analysis deliverables and a written report for the PyBer Ride Sharing Data Analysis:
- Deliverable 1: A ride-sharing summary DataFrame by city type
https://github.com/archinarula/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb

- Deliverable 2: A multiple-line chart of total fares for each city type
![Fig 8.png] (https://github.com/archinarula/PyBer_Analysis/blob/main/Analysis/Fig%208.png)
![Pyber Summary Dataframe.jpg] (https://github.com/archinarula/PyBer_Analysis/blob/main/Analysis/Pyber%20Summary%20Dataframe.jpg)

- Deliverable 3:  written report for the PyBer analysis 
https://github.com/archinarula/PyBer_Analysis/blob/main/README_Written_Analysis_Module5%20Challenge.md

## Results

### Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types

### Pyber Summary Dataframe- key highlights:
Based on the summary dataframe and also the multiple line chart the key highlights for the difference of rides between period of Jan -April 2019 are:
- Rural cities had highest average fare per ride and per driver
- Rural cities had lowest number of total rides or total drivers
- Urban cities had the highest total rides (approx 171% more) and Suburban (approx. 88% more) 
- Urban cities had the highest total number of drivers and total fares
- Urban cities had the highest total fares and total drivers than Rural 
- Urban cities had the lowest average fare per ride or per driver

## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
- The drop in the number of ride usage in the rural cities within the months of January to April, 2019 could be due to the low number of available rides and drivers in those cities and allocating more rides & drivers to the rural cities will most likely reduce average fare per ride & driver which will boost ride affordability. 
- The Urban cities can also benefit from more ride allocation within the months of January to April as this will help meet the demands for rides in those months , increase revenue and enhance affordability.
- Mid Feb- Marc end showed peaks in fare for all city types so maybe some additional data around demographic of riders can be gathered around that period to understand what led to spikes and promotional activities for riders can be customized to enhance usage during this period. 




