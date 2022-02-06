# Pyber Rides in Urban, Suburban, & Rural Areas

## Our task is to show ride-sharing data by city type. Using Pandas and Matplotlib, we have created a multiple-line graph that shows the total weekly fares for each city type. We have analyzed how the data differs by city type and how those differences can be used by decision-makers at PyBer. The report below utilized the total number of rides, total number of drivers, and the total fares for each city type to highlight key performance indicators.  

### Our report consists of two technical analysis deliverables results and a summary report. We will cover the following:

  - Deliverable 1: A ride-sharing summary DataFrame by city type
  - Deliverable 2: A multiple-line chart of total fares for each city type
  - Deliverable 3: A written report for the PyBer analysis
---
### Correlation of Data to Underserved Neighborhoods 
 -  Our goal is to correlate underserved neighborhoods to potential barriers in fare-cost per ride. We will present our method for finding the target neighborhood(s). There is one rural city which stands out. In the center of the scatter plot below, there is a rural city with a small circle. The size of the circle correlates to the number of available drivers in the city. We see the Average Fare is average compared to other rural cities, but higher than all Urban & most Suburban average $s per fare. There is demand for rides based on the higher-than-average Total Number of Rides for the city. Based on the available data, we would consider the rural city to be likely underserved. 
### ![Fig1](https://github.com/ScottyMacCVC/PyBer_Analysis/blob/main/Resources/Fig1.png)
---

## Summary of Urban, Suburban, & Rural City Types
  - The data has shown a trend amoung the three city types. Our overall fares per city type reflect a trend towards Suburban & Urban cities. We see a general increase in fare dollars over the time period selected. If we refer back to our first scatter chart and use the same method to find underserved neighborhoods, we can now add in a third measurement with the chart below. We see three blue, Suburban dots near the same yellow, rural city dot we first explored. These blue dots are smaller and indicate a small number of available drivers. We know from the summary chart below, Suburban & Urban areas are showing growth wherease rural areas are shrinking. We would then target the three Suburban cities with low driver counts, but higher-than-average rides and average fare. 
### ![PyBer_fare_summary](https://github.com/ScottyMacCVC/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.PNG)
---

## How replacing the 9th Grade scores affect the following:
   - **Math & Reading Scores by Grade** The majority of our information will remain the same. We isolated the 9th grade at Thomas High School and replaced them with NaN or Not a Number. Math and reading scores for the 10th to the 12th grade will be unaffected by the change. But we will see a correction for the 9th grade, the averages for the 9th grade in the district and all schools will be updated.  
### ![Math and reading scores by grade](https://github.com/ScottyMacCVC/School_District_Analysis/blob/main/Resources/Math%20and%20reading%20scores%20by%20grade.JPG)
  - **Scores by School Spending** We sorted each school into spending buckets. The section $630-$644 contained Thomas High School. The set of data associated with averages and scores will all update as a result of the 9th grade data set removal. 
### ![District Scores & Percentages by Spending Ranges](https://github.com/ScottyMacCVC/School_District_Analysis/blob/main/Resources/District%20Scores%20%26%20Percentages%20by%20Spending%20Ranges.JPG)
  - **Scores by School Size** We sorted each school into shool sizes. The section Medium contained Thomas High School. The set of data associated with averages and scores will all update as a result of the 9th grade data set removal. 
### ![District Scores & Percentages by School Size](https://github.com/ScottyMacCVC/School_District_Analysis/blob/main/Resources/District%20Scores%20%26%20Percentages%20by%20School%20Size.JPG) 
  - **Scores by School Type** We sorted each school into shool Types. The section Charter type contained Thomas High School. The set of data associated with averages and scores will all update as a result of the 9th grade data set removal. 
### ![District Scores & Percentages by School Type](https://github.com/ScottyMacCVC/School_District_Analysis/blob/main/Resources/District%20Scores%20%26%20Percentages%20by%20School%20Type.JPG) 

---
### Four Changes for the School District Analysis
- **1** Removed 9th grade data from Thomas High School 
- **2** Using Dataframes, we built a DF without 9th grade data from Thomas High School and combined it with the existing data 
- **3** Using the new data, we presented the data in several ways such as by math/reading, by grade, spending ranges, school size, and type. 
- **4** We recalculated the new data from the Dataframe and added it to the summaries


## Resources
- Data Source: schools_complete.csv
- Software: Python 3.7.6. Jupyter Notebook with Pandas
