# PyBer Analysis

## 1. Overview of the analysis: Explain the purpose of the new analysis.

The goal of this challenge is to provide ridesharing data visualizations for PyBer in order to promote access to ride-sharing services and determine affordability for underprivileged neighborhoods.

The study is based on data obtained in the form of a CSV file from PyBer. This data has been processed using Python's Pandas to produce a summary dataframe (shown below) as well as a chart generated using the information in the dataframe to visualize the data.


## 2. Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

### Fig 1. Total Fare by City Type
![PyBer_fare_summary](https://github.com/sbellorin/PyBer_Analysis/blob/6f18ed7b7195274a9d3c2a2e4d32a01a3103ac30/analysis/PyBer_fare_summary.png)

The figure 1 chart illustrates that the quantity of money made by the service is fairly steady over the time period studied (January to May). Urban cities generate the most total revenue, followed by suburban and rural locations. When comparing urban and suburban cities, the average connection is `2:1`, while the same relationship between urban and rural cities is `9:1`.

The observed outcome is not surprising, given that cities are expected to generate more revenue because they have more inhabitants than suburban or rural locations.

Figure 1 does not include any information about the cost of the service to its users; for that, see Figure 2 below.

### Fig 2. Summary Dataframe by City Type
![PyBer Summary Dataframe](https://github.com/Peteresis/PyBer_Analysis/blob/407d939297c5f070d6815984562729dd029bd756/analysis/PyBer%20Summary%20Dataframe.png)

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





