# PyBer Analysis

## 1. Overview of the analysis: 

Creating visualizations of rideshare data for PyBer to help improve access to ride-sharing services and determine affordability for underserved neighborhoods.

The study is based on data obtained from PyBer. The CSV file has been processed using Pandas to produce a summary dataframe using chart generated information in the dataframe for data visualization.


## 2. Results

### Fig 1. Total Fare by City Type
![PyBer_fare_summary](https://github.com/sbellorin/PyBer_Analysis/blob/6f18ed7b7195274a9d3c2a2e4d32a01a3103ac30/analysis/PyBer_fare_summary.png)

Figure 1 shows the amount of money made by the service over the time period studied (January to May). Urban cities generate the most total revenue, followed by suburban and rural locations. The average urban and suburban cities connection is `2:1`, while the  relationship between urban and rural cities is `9:1`.

This is to be expected because cities generlly generate more revenue due to their population in comparison than rural or suburban areas.


### Fig 2. Summary Dataframe by City Type
![PyBer Summary Dataframe](https://github.com/sbellorin/PyBer_Analysis/blob/87ab5a256490ea138a1b595a7c3890bc01d6539c/analysis/PyBer_fare_summary.png)

The figures in the summary Dataframe above indicate certain underlying facts that Figure 1 does not. To begin with, there is a huge gap in the `number of rides in urban cities and suburban or rural ones (2.6:1), as well as between urban and rural (13:1)`. Furthermore, `the number of drivers in urban areas is about five times that of suburban cities, and 31 times that of rural towns`. Similarly, the number of rides per driver favors rural and suburban drivers over urban ones. `0.68 Rides/Driver in Urban Cities vs. 1.28 in Suburban and 1.6 in Rural` is the relationship.

When we look at the income created, the `Average Fare per Ride` is 20% lower in urban cities than suburban, and 30% lower in urban cities versus rural.

Rural drivers clearly outperform Suburban and Urban drivers in terms of `Average Fare per Driver`. The ratio is 3.3:1 for rural vs. urban, and 2.4:1 for suburban vs. urban. 

### **Conclusions**

1. Urban cities generate the most revenue for PyBer
2. Customers in Urban cities pay less per ride and therefore drivers earn less per ride
3. Rural areas seem to be underserved and customers in those areas face more expensive fares than in Urban or Suburban cities

## 3. Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

In order to reduce the disparity between Urban, Suburban and Rural cities, we recomend the following:

1. Instead of focusing on just the first third of the year, the study may gain from having extra data points that span the entire year and provide insights into yearly trends.
2. It seems like the Rural cities are underserved, but it would be neccesary to perform a market study to confirm if there is enough demand in this market segment to justify investing in hiring more drivers.  
3. Based on the relationship of Urban cities of `2405 Drivers/1625 Rides = 1.48 Drivers/Ride`, the total number of drivers in Rural areas shold be increased at least to **185** `(78 drivers * 1.48 = 185 drivers)`, but this increase has to be supported by a market study, as explained in #2.
4. Using the same metric as in #3 above, the number of drivers in Suburban cities should be increased to a minimum of **726**





