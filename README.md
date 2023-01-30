# PyBer Analysis

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#Purpose">Purpose</a>
      <ul>
        <li><a href="#Source Data">Source Data</a></li>
      </ul>
    </li>
    <li>
      <a href="#Results">Results</a>
      <ul>
        <li><a href="#Ratio of Rides to Drivers">Ratio of Rides to Drivers</a></li>
        <li><a href="#Average Fare per Ride">Average Fare per Ride</a></li>
        <li><a href="#Average Fare per Driver">Average Fare per Driver</a></li>
        <li><a href="#Total Fares">Total Fares</a></li>
      </ul>
    </li>
    <li><a href="#Conclusion">Conclusion</a></li>
    <li><a href="#Summary">Summary</a></li>
    <li><a href="#Contact">Contact</a></li>
  </ol>
</details>

## Purpose

Compare ride-sharing fares amongst Urban, Suburban, and Rural cities utilizing data visualizations for PyBer to promote access to ride-sharing services and determine affordability.

### Source-Data 
Utilized Python's Pandas to produce a summary dataframe and chart.


## Results: 


![PyBer Summary](Resources/results_summary_table.png)

### Ratio of Rides to Drivers
- Urban cities have 1.48 times the number of drivers to rides
- Suburban cities have 1.27 times the number of rides to drivers
- Rural cities have 1.6 times the number of rides to drivers

The observed outcome is not surprising, given that cities are expected to generate more revenue because they have more inhabitants than suburban or rural locations.
### Average Fare per Ride
- Urban cities have the lowest average fare per ride at $24.53
- Suburban cities have the second highest average fare per ride at $30.97
- Rural cities have the highest average fare per ride at $34.62
When we look at the income created, the `Average Fare per Ride` is 20% lower in urban cities than suburban, and 30% lower in urban cities versus rural.
### Average Fare per Driver
- Urban cities have the lowest average fare per driver at $16.57
- Suburban cities have the second highest average fare per driver at $39.50
- Rural cities have the highest average fare per driver at $55.49
Rural drivers clearly outperform Suburban and Urban drivers in terms of `Average Fare per Driver`. The ratio is 3.3:1 for rural vs. urban, and 2.4:1 for suburban vs. urban. 


![Total Fare by City Type](analysis/PyBer_fare_summary.png)

### Total Fares
- Urban cities have the greatest total fares at $39,854.38
- Suburban cities have the second highest total fares at $19,356.33
  - 2.06 times lower than urban cities

- Rural cities have the lowest total fares at 4,327.93
  - 9.2 times lower than urban cities
  - 4.47 times lower than suburban cities


## Conclusion

1. Urban area generate higher revenue for PyBer, very high 'supply & demand' of drivers
2. Customers in Urban areas pay less per ride, 'supply' of rides is higher than 'demand'
3. Rural areas have lower 'supply' of drivers hence customers face more expensive fares compared to Urban or Suburban areas

## Summary

### Business recommendations 

In order to reduce the disparity between Urban, Suburban and Rural cities, we recomend the following:

1. Collect extra data points that span the whole year; for more accurate yearly trends
2. Rural cities are underserved, incentivize becoming a driver in rural (and suburban) areas; potentially may motivate drivers to midrate from urban areas  --> Create goal to raise minimum drivers by 10%

## Contact
Huzaifa Hussain | https://www.linkedin.com/in/huzaifa-s-hussain/





