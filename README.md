# surfs_up

## Overview of the statistical analysis (The purpose of the analysis is well defined.)
With the fanciest and cleanest beach, Oahu island is one of the most popular islands around the world. There are millions torists visit Oahu island every year which makes the island is a potential successful place for surf and ice cream shop business. In order to determine if the surf and ice cream shop business is sustainable year-round in Oahu, it is crucial to have a well weather analysis, specifically for the months of June and December. This analysis provides the temperatures in June and December to help W.Avy make plans for the business.


## Results (There is a bulleted list that addresses the three key differences in weather between June and December. )
Utilizing python and SQLite, this project provides through analysis about the tempature in June and December.

- June avg temp - 74.9°F / December avg temp - 71.0°F
  - Similar averages indicate the temperatures in Oahu stay relatively steady in the 70's year round
- June min temp - 64.0°F / December min temp - 56.0°F
  - June's lows still provide good surfing and ice cream weather as December's lows could show less opportunities for both surfing and ice cream
- June 75th percentile - 77°F / December 75th percentile - 74°F
  - Indicates 75% of the time the temperature is in the middle to upper 70's

![june_temps](june_temps.png)
![dec_temps](dec_temps.png)

## Summary (There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December.)
Additional analysis could help solidify the business case.

- Query to view precipitation statistics during June and December
  - This would show the relationship between temperatures and precipitation
- Query to view average temperatures and precipitation levels at different stations
  - This could help narrow down the optimal location for the shop