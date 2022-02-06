# Pyber Rides in Urban, Suburban, & Rural Areas

## Our task is to show ride-sharing data by city type. Using Pandas and Matplotlib, we have created a multiple-line graph that shows the total weekly fares for each city type. We have analyzed how the data differs by city type and how those differences can be used by decision-makers at PyBer. The report below utilized the total number of rides, total number of drivers, and the total fares for each city type to highlight key performance indicators.  

### Our report consists of two technical analysis deliverables results and a summary report. We will cover the following:

  - Deliverable 1: A ride-sharing summary DataFrame by city type
  - Deliverable 2: A multiple-line chart of total fares for each city type
  - Deliverable 3: A written report for the PyBer analysis
---
### Correlation of Data to Underserved Neighborhoods 
 -  Our goal is to correlate underserved neighborhoods to potential barriers in fare-cost per ride. We will present our method for finding the target neighborhood(s). There is one Suburban city which stands out. In the center of the scatter plot below, there is a Subruban city with a small red circle. The size of the circle correlates to the number of available drivers in the city and the city's circle is tiny. We see the Average Fare is higher compared to other Suburban cities and higher than all Urban fare averages. There is demand for rides based on the higher-than-average Total Number of Rides for the city. Based on the available data, we would consider the Suburban city to be likely underserved. 
### ![Fig1 Edit for Challenge](https://github.com/ScottyMacCVC/PyBer_Analysis/blob/main/Resources/Fig1%20-%20Edit%20for%20Challenge.png)
---

## Summary of Urban, Suburban, & Rural City Types
  - The data has shown a trend amoung the three city types. Our overall fares per city type reflect a trend towards Suburban & Urban cities. We see a general increase in fare dollars over the time period selected. If we refer back to our first scatter chart and use the same method to find underserved neighborhoods, we can now add in a third measurement with the chart below. The scatter plot shows three additional red, Suburban dots near the same red, Suburban city dot we first explored. These red dots are smaller and indicate a small number of available drivers. We know from the summary chart below, Suburban & Urban areas are showing growth wherease rural areas are shrinking. We would recommend targeting the four Suburban cities with low driver counts, but higher-than-average rides and average fare. 
### ![PyBer_fare_summary](https://github.com/ScottyMacCVC/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.PNG)
---
### Three Disparities Among the City Types
- **1** The vast majority of the ride fares come from Urban areas. The data above does show four Suburban cities which stand out, but it may be wise to view the three city types seperately. Foe example, the image below show a few cities toward the top right of the graph with low drivers and good KPIs. We know Urban areas are typically successful and these cities would be targeted using our analyis method. 
### ![Urban Only](https://github.com/ScottyMacCVC/PyBer_Analysis/blob/main/Resources/Urban%20Only-%20Edit%20for%20Challenge.png)
- **2** Rural cities may have far more to offer than we are giving credit. The data shows rural areas as overall low value, but the area may still be underserved. The average fare is far higher, but there is a low number of rides. It makes sense for Urban & Suburban areas to receive focus due to the number of rides needed. But utilizing a similar method to the Urban city types, we can work with rural cities, only, and find correlations between low driver counts and higher-than-average fares. 
- **3** Our data is only Winter months. There may be more problems encountered in rural areas during the 1st qtr of the year. We will want to test the same data but for the other quarters. Advertising for more drivers in an area during seasonal demand, coupled with higher than average rates, is a great way to recruit in areas with low number of available drivers. Our drivers receive more income and our users receive the ride they request at a potentially more fair price. 


## Resources
- Data Source: city_data.csv & ride_data.csv
- Software: Python 3.7.6. Jupyter Notebook with Pandas
