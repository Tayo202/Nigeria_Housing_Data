
# Nigeria_Housing_Data

![housing](https://github.com/Tayo202/Nigeria_Housing_Data/assets/97166079/1e263ceb-0e37-40c7-907e-866b357b292e)

## Introduction
The Data file is a csv document listing states and the properties therein. The Dataset is not so comprehensive with detailing on states like Lagos and Abuja.

_**Disclaimer: This is believed and treated like a dummy data, therefore inferences drawn are fictitious. Thank you**_

## Problem Statement
The question posed from the dataset includes: 
1. Overview exploratory examination of the dataset
2. To determine the average prices of housing per states, towns in Nigeria
3. To know states with low housing volume, pricing, and standard of living.

## Skills Demonstrated
The following Excel concepts were demonstrated:
- Power Query
- Power Pivot
- Data Cleaning
- Calculated Fields
- Data Visualization

## Data Sourcing
The data was sourced from Kaggle and by extension Nigeria Property Centre.

## Modelling
No Modelling was done as the dataset consists of only one Table.

## Analysis and Visualization
### Overview
The Nigerian Housing Data consist of eight (8) columns and a little above 24 thousand rows. This is a highly limited data source as Nigeria’s population stand at above 200 million individuals, estimating the national average of 6 persons per home, there should be over 30 million records (rows). Furthermore, the descriptive characteristics are also limited without information such as square ft per home, urban-rural delineation and non-capturing of all states within the country. 
This results in data skew especially in states like Lagos and Abuja, were there more focus.
Therefore, this data analysis should be taken as a sample analysis and not the real population picture. 

![overview](https://github.com/Tayo202/Nigeria_Housing_Data/assets/97166079/7667497e-3885-4a1d-b074-6aa201d36426)

### States with at data counts of above 100 are listed above.
The average bedrooms in each state ranges between 3 and 4.5, while Lagos ranks highest for highest home prices with over 300 million naira per home.
The count of title in Lagos is above 15,000 while the next in line Abuja is not up to 5,000, because of this skew Lagos dwarf other state in all other comparison.

![states with over 100 data](https://github.com/Tayo202/Nigeria_Housing_Data/assets/97166079/15ab699b-4bf3-4155-aa28-f5f5bd057666)

### Average Prices
Drilling down into towns, viewing average price, count of title, and amenities, we see an above title average prize in Guzape district, Maitama district and Ikoyi, which signifies reduced supply of properties which accounts for the high increase in average prices of houses in these towns. 
However, the opposite is true for Lekki, where there is a high supply of properties, and a corresponding low average price in comparison to the above towns.

![Average Pricing](https://github.com/Tayo202/Nigeria_Housing_Data/assets/97166079/4695868c-cd99-4900-bb4d-7f6c994a579f)

### Low Count of Titles

![Screenshot 2023-09-05 075143](https://github.com/Tayo202/Nigeria_Housing_Data/assets/97166079/eb452943-ecf5-45cd-abda-4328515b91a9)

Of the towns with low count of titles, Mowe, stands out with high count of titles. However, the average price reveals some insights, Epe and Kuje average prices are like that in Mowe, despite the high number of count titles in Mowe, a significance of high supply. Highest prices are seen in Aniocha South, Ibeju, Nasarawa and Ogijo.


### Poor Housing

A calculated field termed “Poor Housing” was created using a formula where the number bedrooms was higher than the toilets in the house. This is a field that can be used by government to identify, areas of poor sanitary system, and targets in periods of communicable diseases. The poor housing indices appeared in three (3) states, Cross River, Kano and Kastina. However, due to low data the details could not be drilled down for more specificity.

![Poor Housing](https://github.com/Tayo202/Nigeria_Housing_Data/assets/97166079/6e710fda-b467-4a4e-b80b-43c40b332257)

## Conclusion and Recommendation
Although the data was limited a few inferences were drawn, Houses in Ikoyi are the most expensive in Lagos state, other expensive houses were seen in Guzape, and Maitama in Abuja. Cross river, Kano and Kastina fall into the poor housing category therefore the governments in the respective states should work on legislation to improve standard housing construction.

View the comprehensive dashboard [here](https://www.linkedin.com/posts/akintayo-o-akinpelu_nigeria-housing-data-activity-7107987202948632576-T_O4?utm_source=share&utm_medium=member_desktop)

**Thank You**
