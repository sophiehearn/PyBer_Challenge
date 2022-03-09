# PyBer Rideshare Data Challenge

PyBer leadership is interested in analyzing a large amount of its internal data to learn more about performance in different areas of the company. They are looking for visualizatoins and analysis to help future decision-making for the organization. 

## Overview 

For this project, PyBer has requested an analysis of its ridesharing data broken down by city-type -- rural, urban, and suburban. From this, they are hoping for more insight on where to invest in the future of the company. 

## Results 

The first useful results came in the form of this summary table: 
![image](https://github.com/sophiehearn/PyBer_Challenge/blob/main/Resources/Image%201.jpg?raw=true)
From this, we can learn that most of PyBer's business is conducted in urban areas, making up the majority of rides, drivers, and total fares. 
However, the average fare per ride and per driver is significantly lower in urban areas, and highest in rural areas. Although this analysis doesn't provide details, this may be because individual rides are typically longer in suburban areas than urban areas, and longest in rural areas, where destinations are typically farther apart. 
Another important note from this table is that there are significantly more drivers reported than total rides in the urban setting. This means that there are at least 780 drivers who provided 0 trips, unless some drivers are counted multiple times when working in different cities.

Further analysis also allowed us to create this graph displaying total fares over time by city type: 
![image](https://github.com/sophiehearn/PyBer_Challenge/blob/main/Resources/Fare_by_Week.png?raw=true)
This chart also shows us that total fares are highest in urban areas, but additionally gives us a better idea of the variability of fares. It appears from the graph that there was a spike during the last week of February for all city types - urban, rural and suburban. Beyond that, the variability in fares does not appear to be correlated between the three types, and it seems most consistent in suburban and rural areas. 

## Analysis

My next recommendation for this data analysis would be to add ride lengths to the dataset, or a similar statistic, like rides per hour. This would help determine the wages of the driver - how much they earn per hour, rather than per ride. 

This current data set shows that there is a high demand for PyBer's services in urban areas. However, PyBer appears to have too many drivers on its roster in the urban areas. Since this is a gig job, they are likely not paying the drivers for rideless shifts, but signing people up to be drivers takes company time and resources. Based on this analysis, they should likely stop any efforts to recruit more drivers in urban areas. 

Although there is relatively lower demand in rural areas, PyBer is able to charge much more per ride. There are also fewer drivers compared to the number of rides, and the variablity in rides appears smoother. I would recommend looking further into the rural market. Thee urban market may be saturated - clearly there is a need, if smaller, for ridesharing in more rural areas, and PyBer could lead that charge.