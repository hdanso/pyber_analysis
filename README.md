# Analyzing PyBer Ridesharing Data

## Project Purpose
The purpose of this analysis was to determine how ridesharing data, such as the total weekly ride fares differed between urban, suburban, and rural cities. Using Python Pandas and Matplotlib, weekly fare trips from January 1, 2019 - April 30, 2019 for each city type were calculated and visualized on a line graph. Data from the city_data.cvs and ride_data.cvs, which includes data on PyBer trips and drivers for several cities over a 4 month period, was analyzed to build these insights.

## Analysis Results 
Among the 3 city types, urban cities had the highest total weekly fares between January 1, 2019 - April 30, 2019, as shown in figure 1 below. Urban city weekly fares ranged from $1661.68 to $2470.93. In comparison, rural cities had the lowest total weekly fares, as weekly totals ranged between $67.65 and $501.24.  In addition, suburban weekly fares ranged between $721.60 and $1412.74. 

![Pyber_fare_summary](https://user-images.githubusercontent.com/96188669/192671649-6b0eddca-bf5b-4721-bc79-479d60cf8570.png)


Comparing the ride data in figure 2, urban cities had the highest total rides (1625), while rural cities had the lowest total of 125 total rides. Suburban cities had a total of 625 rides taken. Looking at driver data, urban cities had more than 30x the drivers (2405) than rural cities (78) and almost 5x more than suburban cities (490 drivers in suburban cities).

However, average fares per ride and average fares per driver were significantly different for urban cities ($24.53	and $16.57) respectively, than for rural cities, where average fare per ride and per driver is $34.62 and $55.49 respectively. For suburban cities, average fare per ride was $30.97 and average fare per driver was $39.50.

Finally, total ride fares for urban cities ($39,854.38) were almost 10x that of rural cities total fares ($4,327.93). Suburban cities fell in between the two, with a total fare of $4,327.93.

![DF 1](https://user-images.githubusercontent.com/96188669/192671910-24bc94c9-ca45-44d6-9daa-ee779336b3c7.png)


## Proposed Recommendations 
Based on this data, to address the disparities between the 3 city types, the CEO should consider increasing the number of drivers there are in rural cities. Because of the scarcity of drivers, the potential for an increased revenue from more trips is lost. Therefore, an increase in the number of drivers could lead to an increased revenue and decreased total fare gap between rural and urban cities. The CEO should also consider focusing marketing efforts within rural cities to increase their ridership. Increasing their ridership will lower the average fare per ride and per driver ratios to be closer to urban city averages. Finally, the CEO can also increase ridership by offering lower fares for trips within rural cities. A reduced fare will allow for more individuals to afford trips and increase the frequency they use the service. Building a good reputation with individuals can help the overall growth of ridesharing services in rural cities overtime.
