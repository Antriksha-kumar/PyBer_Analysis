# Overview of the analysis:

This analysis is done on a set of data which contains the details of all the rides covered by the drivers of Pyber, a ride sharing platform. This data set is used to analyze the pattern and create visualizations to support the insight that were found.

The data is provided in two seperate **.csv** format files.

**1. City_data.csv** - It contains details on Citi name, no of drivers in that city and city type.

---
<img src = ".\Resources\City_data_df.png"></img>
---

**2. Ride_data.csv** - It consists of city name, the date of ride, fare amount in USD and a unique ride id.

---
<img src = ".\Resources\ride_data_df.png"></img>
---

We have analyzed both of the data sets and our findings are explained in beow sections.

# Results of Analysis

After analyzing the given data we concludedt the summary as below:

---
<img src = ".\Resources\pyber_summary_df.png"></img>
---

1. We can see that the total number of drivers and Total fare generated is **directly proportional** to no of Total rides.
    While on the other hand, **Average Fare per Ride** and **Average Fare per Driver** are **inversely proportional** to the no of **Total Rides**.

2. The ride sharing is used mostly in the Uran cities and then it keeps on decreasing as we go towards Suburban and further to the Rural cities.

3. Also from the summary we can assume that the number of drivers in Urban cities is more then what the demand is. As we can see that there may be many drivers who may not have been contacted as **total no of Rides** taken is almost **30% less** then the **no of Drivers**.

4. Since the **Total Rides per driver** decreases from Rural to Suburbabn and then at last to Urban cities, hence we can assume that there is a scope for more drivers in Rural and Suburban areas. 

5. We can observe that **average fare per ride** is **higher in rural areas** which may indicate that each ride covers **longer distance** or it could also say that the **rates are higher in Rural areas**. Same can deduced about the Suburban cities when compared to the Urban city's rides data.

At a glance, the chart is portraying what was an expected outcome i.e. **an overall higher volume in total rides as well as fares from the urban cities, lowest volume from rural cities, while suburban cities are sandwitched between the formers.**

---
<img src = ".\analysis\PyBer_fare_summary.png"></img>
---

# Summary:

After observing the above patterns in the given data we can recommend as below:

1. Fare rates seems to be on higher side in the rurall area substantially then the ones in Urban. This may be discouraging for some potential customers.
2. Availability of drivers in Urban area looks to be a lot more then the demand. There should be focussed recruitment based on the demands projections.
3. There should be a greater focus on the marketing of service in rural and suburban areas as the demand seem sto be more then the available drivers.

Given data period is from Jan 2019 to May 2019. So in order to identify the insights and patterns and make any recommendation we should analyze the data for a longer period.