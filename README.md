# PyBer Analysis

## Purpose of Analysis
The ride-sharing app company, "PyBer", wants all the rideshare data from January to early May of 2019 analyzed and represented in a compelling visualization  for the CEO. Creating visualizations of the rideshare data for PyBer can help improve access to ride-sharing services and determine affordability for underserved neighborhoods. The purpose of this analysis is to create a summary DataFrame of the ride-sharing data by city type with the use of Python and Pandas, and create a multiple-line graph that visually illustrates how the total weekly fares for each city type differ from another. 



## Results

#### Summary DataFrame:

![module 5](https://user-images.githubusercontent.com/75760493/105730149-a1d3ac80-5ef3-11eb-88dd-f5ea16a02bb0.PNG)

Based on the Summary DataFrame shown above, the total rides were substantially different between the city types. In urban citiess, the total ride were 1625, which is 2.6 times the total rides in suburban cities (625) and 13 times the total rides in rural cities (125). Since the number of drivers contribute to the total rides, it's expected that the higher the total rides, the higher the total drivers will be, which is shown in the Summary DataFrame. As the Summary DataFrame shows, urban cities have many more drivers (2405) than the suburban cities (490) and the rural cities (78). This shows that the higher the population, the higher the demand for rideshare drivers, which would inevitably lead to a higher supply of drivers to meet this demand. 

While the Summary DataFrame shows the higher popluated urban cities have more rides, drivers, and a higher total fare, however the lower populated rural cities have a higher average fare per ride and average fare per driver. Rural cities lead the group with the highest average fare per ride at $34.62 per ride, which is $3.65 more per ride compared to suburan cities, and suburban cities cost $30.97 per ride, which is $6.44 more per ride than urban cities, which costs $24.53 per ride. This is probably because urban cities have more buildings in close proximity to each other, which would lead to shorter distances of the rides and then result in lower fares per ride. While in rural areas, the ride would be over a longer distance since rural areas have their buildings more spaced apart, which would then lead to the higher fares per ride. 

The average fare per driver acts similarily to the average fare per ride for each city. Rural cities lead the group with the highest average fare per driver at $55.49 per driver, which is $15.99 more compared to suburban cities, and suburban cities cost $39.50 per driver, which is $22.93 more expensive per driver than urban cities, which costs $16.57 per driver. The reasoning behind the drastic difference bewteen cities is because there's less of a supply of drivers to meet the demand of the population in the less populated cities. This would lead to the fare per driver to increase so that the city can ensure that they have enough drivers to meet the demand of the population. Similarily to average fare per ride, the less populated rural cities most likely would have rides longer in distance compared to urban cities, which would then lead to a higher fares.

#### Total Fares by City Type:

![PyBer_Fare_Summary](https://user-images.githubusercontent.com/75760493/105730021-7bae0c80-5ef3-11eb-9fd6-c65b20d05783.png)

The multiple-line chart "Total Fares by City Type" plots the trends of total fares for each city type between January and April 2019. From the yellow trendline, urban cities totaled around $1600-$2250 from January to April. From the red trendline, suruban cities totaled around $700-$1300 from January to April. From the blue trendline, rural cities totaled around $300 from January to Feburary. The chart further demonstrates similar peak times in all these types of cities. One noteworthy peak in total fares among urban, suburban, and rural cities occurred sometime at the end of February 2019.

## Summary

Recommendations to address disparities between cities:

- One suggestion would be to create some sort of incentive program to encourage more drivers to provide rides in rural and suburban areas, which would then help decrease the fare amount the customer would have to pay for a ride while also increasing the total fares. 
- Another suggestion would be to put a cap on the amount of drivers urban cities can have. From the Summary DataFrame, both rural and suburban cities had more rides than drivers, while the urban cities had more drivers than rides. Since urban cities had more drivers than rides, this led to a really low driver fare. It appears that the urban cities might have too many drivers to where the drivers aren't making as much money as those in smaller cities.
- Also, setting a mileage cap for each ride in rural and suburban cities would help reduce the fare per ride for the customer, while also reducing the fare the driver is making in order to get averages that mimic urban cities.
