# PyBer_Analysis

## Overview
The purpose of this analysis was to display CSV data for PyBer in a more informative way so that business decisions can be made based on what the data says. This was done by using Pandas Dataframes to display and graph information such as total and average ride counts, fares, as well as drivers by city type. This all culminates with a line graph showing average total fares by city type per month. 

## Results
As shown here in figure 3, the average fare price is highest in rural areas at over $36. That's %50 higher than in urban cities and about 20% higher than suburban cities. It seems very lucrative to be a rural PyBer driver! The longer distances needing to travel are a likely contributing factor, given rural locations are, by definition, farther away from most destination points in a given area. 

![alt text](https://github.com/Jgray353/PyBer_Analysis/blob/main/analysis/Fig3.png)

And as we see in figure 4, there is between 4-9 times more drivers in urban cities than rural. Supply and demand is certainly bearing out, given average fare price is much higher in rural cities. Rural cities also have the lowest number of drivers. 

![alt text](https://github.com/Jgray353/PyBer_Analysis/blob/main/analysis/Fig4.png)

And finally, in the Total Fare by City Type chart, we see what we'd expect with urban drivers averaging the highest monthly total fares. 

![alt text](https://github.com/Jgray353/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png)

## Summary 

It appears urban cities are well served with ride sharing, as total number of rides is over twice the total of rides in suburban and urban cities combined. Suburban and rural cities seem to need help. One thing I can think of to help is offering drivers bonuses for taking fares in certain areas. And you can use the date data we gathered and also build a dataframe that holds time so you can specify dates/times for promos based on business needs.

That would likely increase total numbers of drivers and rides in those areas. And though it would decrease some, those areas bring in more per fare on average by a big margin already. 

Another idea to help is to provide promos to customers (first few miles free, for example) in suburban and rural areas. That should increase requests for ride sharing in those areas, and bring more drivers to them. 

My last recommendation is to use the monthly earnings graph to get further details on when to enact promos. We see declines in earnings for suburban drivers while rural driver's earnings remains flat. And this is between March and April. Perhaps the urban drivers would like to earn extra money on those rural and suburban fares. 
