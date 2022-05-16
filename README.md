# PyBer_Analysis

## Overview 
### Background
The purpose of this dive into PyBer ride-sharing data to is garner insights for the company's decision makers which will help them steer a path for PyBer's future and growth. This early probe will specifically be looking what the data tells us about fares, rides, and drivers per city type.  City type is classified as rural, suburban, or urban.  

### Resources
-Data Source: [city_data.csv](https://github.com/Bulzeye89/PyBer_Analysis/blob/main/Resources/city_data.csv), [ride_data.csv](https://github.com/Bulzeye89/PyBer_Analysis/blob/main/Resources/ride_data.csv)<br>
-Software: Python 3.7.11, Anaconda 4.12.0, JupyterLab 3.3.2

## Results
Some key findings after aggregating and analyzing the data are:
- There are almost 5 times as many urban drivers as suburban drivers and 30 times as many urban drivers as rural drivers.
- There are 2.6 more total urban rides than suburan rides and 13 times more total urban rides than total rural rides.
- The average urban fare is 29% less than the average rural fare and 21% less than the average suburan fare. 
- The average fare per urban driver is 70% less than the average fare per rural driver and 58% less than the average fare per suburban driver. 
- 62% of total fares and 68% of total rides are from urban cities while 80% of drivers are based in urban cities as seen in the graphs below.
- On a weekly basis, urban fares consistently outpace rural fares by 4 times and suburban fares by 2 times as seen in the graph below.  

<p float="left">
<img src="https://github.com/Bulzeye89/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png" 
</p>  



## Summary: 
Based on the findings of this initial analysis, my business recommendations would be to placing a cap on number of drivers or setting limits on how often drivers have to be active to remain eligible to drive for PyBer depending on the city type.  The data that was analyzed for this project has 1,625 total urban rides and 2,405 total urban drivers.  Urban markets may be oversaturated with drivers and it is worth looking into how 780 drivers didn't even have 1 total ride driven.  Adding more drivers to both suburban and rural areas could be lucrative as these types of cities typically have less elaborate public transport system.  It's possible that more total rides could be given if more drivers were available.  Further analysis that could be considered to find ideal number of drivers per city would be to look at population counts of cities as well as filtering the date/timestamp of the rides to find peak service times.  With this data, PyBer could become more control the number of drivers hired as well as the availability of those hired drivers to drive maximum revenue.   
