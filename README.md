# PyBer_Analysis
## Overview
The overview of the project was to create the following:
* a ride-sharing summary DataFrame by city type
* a multiple-line chart of total fares for each city type from the beginning of January through the end of April for 2019
* a written report providing analysis of the main components of the data as well as three business recommendations to the CEO of PyBer to provide solutions to address any distinctive differences between the three city types of Urban, Suburban or Rural. 
## Results
The main focal points of the data.
* One of the main differences in PyBers data amongst different city types is that the total amount of rides decreases as you get further away from the urban area. From urban to suburban the number of rides decreases by 260% and from urban to rural the number of rides decrease by 1300%. This is to be expected as rural areas are less densely populated and generally the population relies upon their own mode of transportation.
* In comparison to the total amount of rides is the total amount of drivers. A good way to measure the number of drivers in each area is to compare the number of drivers to rides to create a ratio to evaluate where an optimal number of drivers may exist compared to rides. For the three area types, the ratio of drivers to rides are as follows: 
    * Urban : 1.480 
    * Suburban : .784
    * Rural : .624
    
    As the data show there is a significantly higher number of drivers per ride in the Urban area whereas Suburban and Rural are both closer to 70%.
* As the bubble chart displays below there is a negative linear correlation between the average fare and the total number of rides per city further reinforcing that the more drivers per city the less on average drivers profit in fares. 
![PyBerBubbleChart](https://user-images.githubusercontent.com/95573310/203676650-0579eb4c-2487-4114-9135-d83372139b12.png)

* We also take a look at the total fares by city type which all three types of cities have a relatively constant amount of Fares in the months of January through April. There is a slight uptick in fares in the middle to end of February for all cities due to some event or holiday during that time period. Taking a further look into the seasonality and high ride demand periods for each type of city would benefit PyBers optimal driver allocation schedule. 
![sum_fares_city](https://user-images.githubusercontent.com/95573310/203676671-b31f934a-0b81-4a7c-9800-77e663ca6588.png)

    
## Summary
* The three recommendations that can be made to assist Pyber in its growth of market share as well as future profits and employee retention can be summarized as such:
    1. To optimize the number of drivers per city type to create a more equal fare per ride target per city type to improve employee retention. 
    2. To perform marketing research to see if there is more opportunity for growth in rural areas to make PyBers service more appealing to that demographic to capture more market share. 
    3. To conduct further analysis on customer satisfaction, utilizing metrics such as ride wait time, distance of ride (per city type) and to create a rating system to allow riders to review their driver and vice versa, drivers to review their drivers. 
