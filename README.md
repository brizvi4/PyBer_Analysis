# PyBer Analysis

## Overview

For this project, I was asked by V. Isualize to use Python and Pandas to create a summary DataFrame of the ride-sharing data by city type. And then using matplotlib, I had to create a multiple-line graph that shows the total weekly fares for each city type. 

I first made a summary dataframe using the two csv files (city_data.csv and ride_data.csv) given to me. In this dataframe, I populated the following values: Total Rides, Total Drivers, Total Fares, Average Fare per Ride and Average Fare per Driver. After creating this table, I formatted it to make it more presentable. In the second part of this project, I made a dataframe which had fare information for all dates between 2019-01-01 through 2019-04-28 for each city type (rural, urban and suburban). On this DataFrame, I applied the resample() function to create another dataframe to get the total fares for each week. Finally, I used object-oriented interface method and the df.plot() method to create a graph which shows Total Fare by city Type for the months of January, February, March and April. 

## Results

- From the pyber_summary_df DataFrame, we can see that Urban cities have the most number of rides, drivers and total fares while Rural cities have the lowest of these attributes. Average Fare per Ride and Average Fare per Driver are the highest for rural cities and lowest for urban cities. It cann be seen from the table that since there are many drivers in Urban cities, the average fare per ride is less. Whereas, in the rural cities, there is a shortage of drivers, do fares are also high. In fact, in urban cities, there are more drivers than rides. This also brings the average fare per Driver very low. Please see the below image. 

![image](https://user-images.githubusercontent.com/95254809/152719233-d0fd8968-0e91-4e8d-9db8-efb6e8dd957a.png)

- By looking at the Total Fare by city Type graph, we see a very obvious trend that throughout the four months, Urban fares have always been the highest, suburban second highest and rural the lowest. It can be clearly inferred from this information that many people use Pyber in Urban cities. This brings the total fare amount very high even though average fare per ride is the lowest in urban cities. Most people in rural cities use thier own transport.  

![image](https://user-images.githubusercontent.com/95254809/152719838-d98f06ce-7711-4b7a-966e-94da967d628f.png)

## Summary

Following are the recommendations I would give to the CEO:

- It would be a good idea to shift some of the drivers in urban cities to rural and sururban areas. This would decrease the average fare per ride in rural and suburban ciies. In addition, this will also increase the average fare per driver in Urban cities.
- In order to encourage more people to use Pyber in rural cities, it would be better if the company reduces the average fare per ride so that more people can afford and use Pyber.
- In Urban cities, Pyber should invest in advertising so that number of rides increase. Pyber has many dirvers in the urban cities and they can easilty cater for the growing demand. 
