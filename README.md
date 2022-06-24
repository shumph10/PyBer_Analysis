# PyBer_Analysis
Analysis of PyBer ride sharing data for multiple city types (rural, suburban, and urban) was done to determine relationships between location, cost, number of drivers, and amount of rides. 

##**Resources**
Data Sources: city_data.csv, PyBer_ride_data.csv, ride_data.csv. 
Software: Python 3.9.7, Jupyter Notebook 6.4.0

##**Overview**
PyBer, a python-based ride sharing company requested analysis of data for rides from 2019 accross different city types. The types of city (rural, suburban, and urban), number of drivers and riders, and fare were analyized to determine possible relationships. These relationships will be used in future decisions to improve access and affordability of rides. Rural cities were found to have lower numbers of total rides and fares, and urban cities were found to have higher total rides and fares. Additionally as fare prices went up, total of rides get down thus having a negitiave correlation. Graphs representing these relationships can be found in the analysis folder. With these relationships determined, an in depth analysis of weekly total fares by city type was desired. Dataframes were created in Jupyter Notebook to house the sorted information and a master line graph was made to depict the differences in total weekly fares by city type.

##**Results**
Relationships between variables for PyBer ride data per city type is as follows:
- Total rides per city type:
  - Urban cities were found to have the largest number of rides, and rural the lowest. 
  - Circle size in graph correlates with driver count per city.
  - Percentage of total rides by city type are as follows:
    - Urban: 68.4%
    - Suburban: 26.3%
    - Rural: 5.3%

![Fig1_PyBer_ride-sharing_data](https://user-images.githubusercontent.com/100040705/163723856-26747ca5-dfcc-47f6-b6af-b766909e7523.png)
![Fig6_%total_rides_by_city_type](https://user-images.githubusercontent.com/100040705/163724723-6d50e920-b732-4044-9f07-baa80db1d512.png)


- Total drivers per city type:
  - Urban cities had the highest number of drivers, suburban had the median amount, and rural had the least amount of drivers. This is show in the graph below. 
  - Mean number of drivers per city type:
    - Urban: 37
    - Suburban: 14
    - Rural: 4 

![fig4_driver_count_data](https://user-images.githubusercontent.com/100040705/163723898-afd91b74-3bb4-4efb-a03e-53469019f24a.png)


- Total fares per city type:
  - Urban cities comprised the highest percentage of total fares, then suburban, and rural comprised the least amount of total fares. 
  - Average fares per city type:
    - Urban: 60.7%
    - Suburban: 30.5%
    - Rural: 6.8%


![Fig5_%total_fare_by_city_type](https://user-images.githubusercontent.com/100040705/163724144-aa360d39-1479-4af5-8de8-a89173533ef1.png)


- Average fare per ride:
  - Rural cities were found to have the highest fares, suburban were next highest, and lowest average fares were in urban cities.
  - Average fares per city type:
    - Urban: $24.53
    - Suburban: $30.97
    - Rural: $34.62
![fig3_ride_share_data](https://user-images.githubusercontent.com/100040705/163724138-d97da98d-2160-4da1-a0f7-4fe2dfaf347d.png)


- Average fare per driver:
  - The highest average fare per driver occured in urban cities, then suburban, and the lowest occured in rural areas. 
  - The mean fare per driver by city type is as follows:
    - Urban: $36.68
    - Suburban: $13.71
    - Rural: $4.29

![fig4_driver_count_data](https://user-images.githubusercontent.com/100040705/163724774-db74ad8d-8e44-48b4-9534-483c3243a3e9.png)


- Total fare by city type:
  - Weekly totals for fare from 01/01/2019 - 04/28/2019 were calculated for comparison of total fares by city types. Urban cities were found to have the highest overall total fare by city type(represented in yellow). Next was suburban(represented in red), then the lowest was rural(represented in blue). Total fare by city type is depicted in the graph below. 

![Total_Fare_by_City_Type_graph2](https://user-images.githubusercontent.com/100040705/163724347-2b5b491d-1be0-45bc-bc88-e7848b88448a.png)

##**Summary**
Based on the relationships established, the lowest area of accessibility occurs in rural areas. The driver count is lowest in these rural areas so recruitment of additional drivers in these cities could be beneficial in increasing availability and driving sales. Total and average fare by city type shows urban cities had majority of fares. Increased marketing in these urban cities where there is high demand for services could additionally improve profit in these areas. Average fare per city type additionally shows a significantly higher fare in rural areas, and total rides per city types graph depicts a decrease in rides as prices increase. Therefore, running promotions or lowering prices in rural areas would improve total rides. If the promotions or price decreases is done with knowledge of potentially higher number of rides profits could improve in these areas as well. 


##**Contact:**
- sarahhumphrey2016@outlook.com
