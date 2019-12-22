# PyBer_Analysis
Module 5

## Dataframe Summary
![Population Type Summary](https://github.com/Calistic/PyBer_Analysis/blob/master/Analysis/SummaryDF.PNG)

This summary aligns with our intuition of how Rural, Suburban, and Urban population types compare to eachother.
- Rural populations have the least Total Rides, while Urban populations have the most Total Rides
  - The same is true for Total Drivers and Total Fares
- Average Fare per Ride is highist for Rural populations and lowest for Urban populations
  - The same is true for Average Fare per Driver
  - This also aligns with our understanding of supply and demand. The ratio of Total Rides to Total Drivers is highest for Rural populations, and lowest for Urban populations. There are more customers than drivers in Rural populations, the opposite is true for Urban populations. See the ratios of Total Rides/Total Drivers below:
    - Rural: 125/78 = 1.60
    - Suburban: 625/490 = 1.28
    - Urban: 1625/2405 = 0.68
      - Implication: The excess of drivers in Urban populations is likely making the Average Fare per Ride the lowest. Getting more drivers in Rural populations would likely lower fares.

## Total Fare by City Type Summary
![Total Fare by City Type](https://github.com/Calistic/PyBer_Analysis/blob/master/Analysis/Total_Fare_by_City_Type.png)

- The graph shows that the first week of January has the least revenue and the third week of February has the most revenut (for Jan-Apr).
- There is an interesting spike in ridership the third week of February across every population type.
  - Implication: We should also compare this spike across multiple years to see if it is predictable. We should ensure we have more drivers during this time to keep customers happy. We may want to ensure our servers can handle this excess load.
- The graph shows that Urban populations generate the most revenue, while Rural populations generate the least revenue
