# PyBer-Analysis
Using Jupyter Notebook, Python, Pandas and Matplotlib, to analyze and visualize ride-sharing data

## Project Overview
In this project, a data analyst in Pyber, is task with analyzing all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO, V. Isualize.
The data analyst is tasked to create several types of visualization to tell a compelling story about the data trough a variety of charts that showcase the relationship between the type of cities and the numbers of drivers and riders, as well as the percentage of total fare riders and drivers, by type of cities. 
The analysis will help Pyber improve access to ride sharing services and determine affordability for underserved neighborhood.

## Resources
- Data Source:  [All Resource Files](https://github.com/GloriaY007/PyBer-Analysis/tree/main/Resources),
                [Charts](https://github.com/GloriaY007/PyBer-Analysis/tree/main/Analysis),
                [Source Code](https://github.com/GloriaY007/PyBer-Analysis/blob/main/PyBer_Challenge.ipynb).

## Overview of the analysis:

1. Create a Bubble Chart for the Ride-Sharing Data
The analysis started based on the preliminary work that was performed in the [PyBer.ipynb](https://github.com/GloriaY007/PyBer-Analysis/blob/main/PyBer.ipynb) data file. 
We started by creating a bubble chart that presented the Ride-Sharing Data by City Type based on the number of rides, the average fare, and the average number of drivers for each city type. This allowed us to visualize the data per city.

  ![PyBer Ride-Sharing Data](https://github.com/GloriaY007/PyBer-Analysis/blob/main/Analysis/Fig1.png)
  

2. Calculate Summary Statistics
Then, we performed some statistical analysis by looking at summary statistics (mean, median, and mode) for the fare, the number of rides, and the number of drivers, for each city type. 

If we compare the average number of rides between each city type, we'll notice that **the average number of rides** in the rural cities is about **4 and 3.5 times** lower than urban and suburban cities, respectively.

To further confirm this, we also created a box-and-whisker plots that visualized Ride Count Data, Ride Fare Data, and Driver Count Data, to determine if there are any outliers.

  ![Ride Count Data](https://github.com/GloriaY007/PyBer-Analysis/blob/main/Analysis/Fig2.png)
  
There is one outlier in the urban ride count data (39 Rides). The city of West Angela has the highest rider count. Also, **the average number of rides** in the **rural cities** is about **4- and 3.5-times lower per city** than the urban and suburban cities, respectively.
  
  ![Ride Fare Data](https://github.com/GloriaY007/PyBer-Analysis/blob/main/Analysis/Fig3.png)

From the combined box-and-whisker plots, we see that there are no outliers. However, **the average fare for rides** in the **rural cities** is about **$11 and $5 more** per ride than the urban and suburban cities, respectively. 

  ![Driver Count Data](https://github.com/GloriaY007/PyBer-Analysis/blob/main/Analysis/Fig4.png)

The **average number of drivers** in **rural cities** is **nine (9) to four (4) times less per city** than in urban and suburban cities, respectively. 

3. Percentage of Total Fares by City Type, Percentage of Total Rides by City Type, and Percentage of Total Drivers by City Type
The last part of the analysis looked at the percentage total fares, total rides, and total drivers by city type.

## Results:

We found that urban cities represent **62.7%** of total fares.There is a greater usage of PyBer in urban cities, therefore, the total fares also higher than suburban and rural cities. The pie chart below shows where the majority of PyBer's revenue occurred during this time period: urban cities.

  ![The percent of total fares.](https://github.com/GloriaY007/PyBer-Analysis/blob/main/Analysis/Fig5.png)

The chart below demonstrate that there is a larger demand for PyBer among riders in urban cities compared to suburban and rural cities. We found that rural cities account for only **5.3%** of total rides.The pie chart below highlights how rides in Urban cities contributed the most to PyBer's overall rides during this five-month period.

  ![The percent of total rides.](https://github.com/GloriaY007/PyBer-Analysis/blob/main/Analysis/Fig6.png)

We also found that rural cities account for only **2.6%** of total drivers. Similarly to the previous charts, we can see that there was also a larger volume of drivers in urban cities compared to suburban and rural cities. Again, the figure below depicts the significance of drivers in urban cities during this time period.

  ![The percent of total drivers.](https://github.com/GloriaY007/PyBer-Analysis/blob/main/Analysis/Fig7.png)

The multiple-line chart "Total Fare by City Type" provides trends of total fares in rural, suburban, and urban cities between January 2019 and April 2019. 
The yellow trend shows how fares in urban cities totaled between $1,600 to $2,300 from beginning to end during this five-month period. On the other hand, the blue trend shows how fares in rural cities totaled around $300 from beginning to end during the same time period. In contract, the orange trend shows how the total fares in suruban cities fall in between urban and rural cities: around $700 to $1,300 from beginning to end during this time. 

  ![The Total Fare by City Type.](https://github.com/GloriaY007/PyBer-Analysis/blob/main/Analysis/PyBer_fare_summary.png)
  
## Summary:

Based on the data that we analyze, we suggest that Pyber:
- There is a larger use of PyBer ridesharing in urban cities, therefore the majority of PyBer's revenue occurs in urban cities. PyBer should maintain and/or improve its approach in urban cities.
- The costs for using PyBer is greater among riders in rural cities than urban cities. Pyber should look into avoiding having discouraged potential riders given the high average fare per ride. Additionally, since drivers in rural cities are earning more than drivers in urban cities, PyBer should avoid having discouraged potential drivers from working with PyBer given the low average fare per driver.
- Pyber could further this analysis by looking into other contributing factors to the high ride costs in rural cities and low driver fares in urban cities, such as travel distance. 

Overall, PyBer ridersharing services are vastly different depending on the city type (rural, suruban, and urban cities) and given the number of rides, drivers, and fares. The data presented here supports that there is higher usage of PyBer ridesharing services in urban cities.


