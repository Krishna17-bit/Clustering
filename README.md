## Overview
This repository contains two Jupyter notebooks that demonstrate the application of various clustering techniques to two different datasets: airline customer data and US crime data. The analysis explores different clustering methods including Hierarchical Clustering, K-means, and DBSCAN to uncover patterns and groupings within the data.

## Datasets Description
Airline Data:
- This dataset comprises information on airline customers and includes features like miles eligible, total bonus miles, and types of miles programs.
Attributes:
- Balance: Miles eligible for award travel
- Qual_miles: Miles qualifying for Topflight status
- cc1_miles, cc2_miles, cc3_miles: Indicates the level of miles earned with different types of mileage credit cards
- Bonus_miles: Total number of bonus miles earned
- Bonus_trans: Total number of bonus miles transactions
- Flight_miles_12mo: Total flight miles in the past 12 months
- Flight_trans_12: Total number of flight transactions in the past 12 months
- Days_since_enroll: Days since enrollment in the frequent flyer program
- Award?: Whether the customer received an award flight (binary: 1 if yes, 0 if no)
  
US Crime Data:
- The dataset includes statistics on violent crimes across different states in the US.
Attributes:
- Murder: Murder rates per state
- Assault: Assault rates per state
- UrbanPop: Urban population
- Rape: Rape rates per state
  
## Files
- Clustering_Airline_Data.ipynb: Jupyter notebook that performs clustering analysis on the airline dataset.
-  Clustering_Crime_Data.ipynb: Jupyter notebook that performs clustering analysis on the US crime dataset.
  
## Analysis Overview
Each notebook explores various clustering techniques:
- Hierarchical Clustering: Used to identify the inherent groupings within the data.
- K-means Clustering: Used to partition the data into K distinct clusters based on the features.
- DBSCAN: Used for density-based clustering, identifying arbitrary shaped clusters and outliers within the data.
  
