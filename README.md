
# Data Analysis:Accidents in London

This is a personal project post my Google Data Analytics professional Certificate. Here I used the data from the TFL open data source to analyze the trends in accidents reported and to try justify the reasons in the trends.

## Objective:
The idea behind the project was to analyze the accidents reported in the year 2019 within Greater London, for the zone governed by Transport for London.

### Data Sources:

Data was collected from the TFL's open data source [TFL Data](https://roads.data.tfl.gov.uk/) . 
The Data files used were 2019-gla-data-extract-vehicle.csv and 2019-gla-data-extract-attendant.csv. 

### Data Analysis and Cleanup

The data was cleaned using R programming.
R Programming code can be found [here](https://github.com/desmon316/Data_Analysis/blob/main/TFL_2019_Accident_Report.R) .

### Data Visualization
 
Detailed Analysis can be found [here](https://github.com/desmon316/Data_Analysis/blob/main/AccidentsInLondon.html)
Here is my [Tableau dashboard](https://public.tableau.com/views/TFL_Accident_Data_Analysis/Story1?:language=en-US&:display_count=n&:origin=viz_share_link)


### Summary

Even though City of London is the central part of London, it has the lowest accidents reported amongst all the boroughs. This can be attributed to the Congestion Zone charges applicable for vehicles. The boroughs around City of London have the highest accidents reported. The boroughs farther away from City of London have lower accidents with exception of Enfield and Barnet. The reason for borough of Barnet to have higher cases than its surroundings may be attributed to M1. This however needs further research. The A10 in Enfield is a high traffic road and this traffic density may be the reason for higher accidents( needs further research).


The accidents occuring during daylight is higher than nights. Personal Cars lead the vehicles involved in accidents. Most of the accidents can be attributed to driver faults as the accident attendant report mentions that there were no obstructions on the carriageway which could have caused the accidents and the road condition was dry for most of the cases.. Parked vehicles leads the main cause of obstructions on carriage way. Highest number of accidents reported were of low severity. 


Women can't be stereotyped as bad drivers :) as it was observed that men were the drivers in more than 50% of the accidents reported. Young Drivers weren't the reason for most of the accidents but those in the middle age were the drivers that caused the highest accidents by age group.


Amongst the days of the week, Friday had the highest cases reported. This may be attributed to the weekend traffic that builds up around London
