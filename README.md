# Surfs Up
## Overview
### Purpose
The purpose of the analysis is to provide temperature trends of Oahu in Hawaii for the months of June and December in order for W. Avy to determine whether or not to invest in our surf and ice cream shop business. We use Python SQLAlchemy, numpy, and pandas to complete our analysis.

### Results

* From our analysis, we filtered for all June temperatures into a list and converted it into a DataFrame. We can see that there are 1700 rows of temperature for June.

![image](https://user-images.githubusercontent.com/108503112/198149393-3a561236-efce-4e2b-bd82-239afe72826e.png) 

* From the DataFrame, we can determine the summary statistics for all June temperatures. We can see that the mean temperature is 74.944118 degrees F, with the min being 64 degrees F and the max being 85 degrees F.

![image](https://user-images.githubusercontent.com/108503112/197891941-ed4cdbc6-09fe-4fab-af16-a8dac13db439.png)

* We also filtered for all December temperatures into a list and convert it into a DataFrame. We can see that there are 1517 rows of temperature for December.

![image](https://user-images.githubusercontent.com/108503112/198149606-4a162d7d-84c2-42dd-b9d9-703febed1e64.png)

* From the DataFrame, we can determine the summary statistics for all December temperatures. We can see that the mean temperature is 71.041529 degrees F, with the min being 46 degrees F and the max being 83 degrees F.

![image](https://user-images.githubusercontent.com/108503112/197892520-487b5cdf-a7f2-4ec1-a522-29d75fe1290a.png)

* For both the June and December temperatures, we can see that the standard deviation is 3 degrees F. 

### Summary
The results determine that in both June and December, the temperature will most likely be warm enough in those two months to open the surf and ice cream shop. However, that is not enough data as we only have temperature statistics for two months out of twelve in the year. 

One additional query I would recommend would be to find the temperatures for all months in the year so we can determine the summary statistics.
Another query I would recommend would be to find the most frequently reoccuring temperature (mode) for each month.
