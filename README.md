# Pyber_Analysis

## Overview of the analysis:

The purpose of this analysis is to create a summary DataFrame of the ride-sharing data by city type. Then we are creating a multiple line graph that shows the total weekly fares by each city type. We then assigned it to functions like groupby() function, count() and sum() on PyBer DataFrame columns to get the total number of rides, total number of drivers, and the total fares for each city type. We have also used the pivot() and resample function to create a multiple line graph. It shows the total fares for each week by city type between 2019-01-01 to 2019-04-29.

## Results:


![alt text](https://github.com/nikmahadeshwar/Pyber_Analysis/blob/main/Results%20pyber1.PNG)

From the above DataFrame we could clearly see that:
* Urban cities has the highest rides, drivers and fare.
* Suburban cities has the second most highest rides, drivers and fare.
* Rural cities has the lowest amount of rides, drivers and fares.
* Although the Urban has the maximum amount of drivers, rides and fares, the Average Fare per Driver is higher for Rural that is $55.49

## Total Fare by city type chart 
![alt text](https://github.com/nikmahadeshwar/Pyber_Analysis/blob/main/Total%20fare%20by%20city.PNG)

From the above Dataframe we are able to see Total Fare by city types by Rural, Suburban and Urban Cities. We can also see that rural area charges more on the ride as compared to Urban and suburban. We can recommend Urban cities to charge more per mile because trips most likely are shorter and drivers are not earning much as per the trip.
