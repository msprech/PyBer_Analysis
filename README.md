# PyBer Ride Sharing Service Analysis

## Overview 

We analyzed data from PyBer, a ride-sharing app company, in order to make recommendations on how to improve access and distribution of services, particularly focusing on how to address underserved neighborhoods. Our report studies how different city types differ by total number of rides, total number of drivers, total fares, and average fare per ride and per driver. 

We then created a multiple line graph to plot the total weekly fare per city type. This data was then used to evaluate different techniques to improve affordability of PyBer rides for underserved neighborhoods.  

## Results 

#### PyBer Summary DataFrame

![PyBer Summary](https://github.com/msprech/PyBer_Analysis/blob/cd68535aba5fe2dfce2a0f806884531048a3e172/Resources/pyber_summary_df.png)

The PyBer summary dataframe shows that total rides given, total number of drivers, and total fares are all significantly higher in urban cities than in rural or suburban cities. Urban cities are also the only city type where the total number of drivers outnumbers the total rides given. As a result, the average fare per ride and per driver are both much lower for urban cities than they are for rural or suburban cities. 

#### Total Weekly Fare Per City Type Chart

![final chart](https://github.com/msprech/PyBer_Analysis/blob/cd68535aba5fe2dfce2a0f806884531048a3e172/analysis/Pyber_fare_summary.png)

The Total Fare by City Type chart plots the fare by city type by week over the course of four months in 2019. As seen in the previous summary dataframe, the fare in urban cities is consistently higher than either the suburban or rural cities. The rural cities once again show the least total fare overall. 

## Summary 

Key changes needed to address the disparities among city types include: 
* Hiring or redistributing more drivers in rural cities in order to bring down the average fare per ride and increase the total rides given. 
* Decreasing the number of drivers in urban cities to meet the reduced need and increase the average fare per driver. 
* Taking the time of year into consideration using the Total Fare chart to determine seasonal needs in each city type. 
