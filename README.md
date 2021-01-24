# PyBer Analysis

## Project Overview

In this project, I helped PyBer create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, I made a multiple-line graph that shows the total weekly fares for each city type. The report you are seeing is the final result summarizing how the data differs by city type and how decision-makers can use those differences at PyBer.


## Resources
- Data Source: city_data, ride_data
- Analysis File Name: PyBer_Challenge.ipynb

## PyBer Analysis Results

![Ride-Sharing Summary by City Type in DataFrame](Resources/DataFrame_CityTypeSummary.png)
- The DataFrame Summary:
    - Overall, we can see that the Urban city type outperformed the other two types in terms of Total Rides, Total Drivers, and Total Fare.
    
    However, in terms of Average Fare per Ride and Average Fare per Driver, it has the least amount of dollars, and Rural had the highest amount of money.

![Total Fare by City Type](Resources/TotalFareByCityType.png)
- The Multiple-Line chart representing Weekly bins and the sum of the fares for each week:
    - Since this graph shows the Total Fare by City Type, combined with the previous summary, we can see that the Urban area got the most fare, whereas Rural generated the least fare. In addition, it shows that the total fare is fluctuated through out from January to April, without any clear sign of a positive or negative trend.
    - There are few weeks during this period that the Rural area almost generated 0$ of the total fare.

## PyBer Analysis Summary

After the analysis, there are three recommendations I have to the CEO for addressing any disparities among the city types:

-  We should retain the same number of Rural-drivers because there are not many needs for a drive in that area. Plus, it has more potential to earn more money per trip and per driver at the current rate.
- From the DataFrame Summary, I see that even though most of the rides happened in the Urban area, it only contains short trips with a small fare per trip. On the other hand, most of the Rural area trips are long trips with a large fare per trip. Nevertheless, it is better to have lots of short trips than nothing, so we should retain the number of drivers in Urban area. If we increase the number of drivers, it will reduce the amount of fare generated per trip and per driver even more.
- Given the limited amount of data we have for this defined period (it would be better if we have the demographic data of those areas), I think the area we should pay more attention to is Surburban. It is currently generating around 26% of the total drives and 30% of the total fares. Even when we increase the number of drivers there to 600 instead of 490 (110 drivers more), the average Fare per Driver is still in good ratios at 32$ (only 7.5$ less than the current rate). With that said, I recommend we do more marketing in the Surburban to get customers to use our app more and increase the number of drivers we have in that area.


