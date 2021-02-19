# surfs_up

## Summary:
The purpose of this analysis was to use Python SQLAlchemy, and Flask to analyze and visualize climate data for preparing to open a surf shop.

## Overview:

### Created Flask App

Created five routes for our flask app: Welcome, Precipitation, Stations, Monthly Temperature, and Statistics.

### Determined the Summary Statistics for the Month of June 

Used Python's Pandas functions and methods, and SQLAlchemy, to filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. Then converted those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

### Determined the Summary Statistics for the Month of December

Used Python's Pandas functions and methods, and SQLAlchemy, to filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. Then converted those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

## Results:

1. June and December have very similar tempertures for the mean and the max. 
2. Standatd deviation for both months were very, but decembers was higher.
3. June has more data points than December.

June:

![Screen Shot 2020-12-05 at 5 13 05 PM](https://user-images.githubusercontent.com/16258584/101269042-bd120f00-372f-11eb-832e-be9a89296941.png)

December:

![Screen Shot 2020-12-05 at 5 13 30 PM](https://user-images.githubusercontent.com/16258584/101269035-9b188c80-372f-11eb-9ff1-cfdc45d3524b.png)

