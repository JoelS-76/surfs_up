# Surf's Up
### Analysis of climate data for Oahu using SQLite and SQLalchemy

The purpose of this analysis is to evaluate the climate data for June and December to determine if W. Avy's surf shop/ice cream stand is a good year-round investment.

## Results from exploratory data analysis

-The average temperature in June is just under 75 degrees. The highest reading was 85 degrees and the lowest was 64.

![image](https://user-images.githubusercontent.com/84299125/129835049-3a2da71b-58fc-4fbe-8598-282756cf9348.png)


-The average temperature in December is 71 degrees. The highest reading was 83 and the lowest was 56.

![image](https://user-images.githubusercontent.com/84299125/129835096-f4fa2cda-1716-45cf-baf4-661dd4179c14.png)

-While the minimum temperatures for the respective months varied significantly, the rest of the readings were only a few degrees different from one another. 

## Summary

Hawaii is in a tropical zone, and therefore sees minor fluctuations in temperature. I would have to say this business would probably succeed year-round based on temperature alone. Tropical areas typically have dry and rainy seasons rather than a true summer and winter, and so precipitation may be a more significant indicator. I have run additional queries to filter the precipitation data for June and December as well. 

### Additional Queries

June precipitation:

![image](https://user-images.githubusercontent.com/84299125/129836217-d3e0285d-f645-46bb-a285-8c288b66fabe.png)

December precipitation:

![image](https://user-images.githubusercontent.com/84299125/129836279-d2435339-c3aa-4820-9127-a67b61f29bd8.png)

As you can see, the difference in precipitation is much larger. I do not know which month has the highest precipitation level, but it would be a simple matter of refactoring the code to retrieve the data for each month. I would expect business to slow down somewhat during the rainy season, but the consistent temperatures should keep things going well enough to stay in business. It would also be wise to set profit margins for the dry season so as to build up a hedge against the slower rainy months.
