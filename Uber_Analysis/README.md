# NYC Uber Data Analysis
The results of this analysis can be very useful to know for Uber drivers. It can allow drivers to plan and optimize the times of day and the locations in a way that can yield an increase in their profits and thus, the profits of the company. After processing the data sets, k-means clustering is performed to extract this knowledge from the data.


### Data sets
The data sets utilized in this analysis can be found [here](https://www.kaggle.com/fivethirtyeight/uber-pickups-in-new-york-city). The 2014 files were combined to create one data set and the 2015 data set was already provided as one file.

The data sets were reduced to include data points from only April, May and June, which are the overlapping months included in both data sets. The data was further transformed for location analysis in order to plot coordinates and for datetime analysis in order to chart and cluster time data.

### Results
The jupyter notebooks in this section include various charts and maps that can give a more detailed look into some of our results. We have been able to determine peak times of rideshare usage as well as the most common locations where rideshares start.

This map, based on 2014 data, shows locations that are most in demand for rideshares:
![](https://github.com/s-saloni/Rideshare-Patterns/blob/master/Uber_Analysis/Charts/Uber2014Map.png)

The two charts below visualize the result of using k-means clustering to extract peak times of rideshare usage. The first one is for Mondays in 2014:
![](https://github.com/s-saloni/Rideshare-Patterns/blob/master/Uber_Analysis/Charts/Uber_Mon2014.png)

The second is for Saturdays in 2014:
![](https://github.com/s-saloni/Rideshare-Patterns/blob/master/Uber_Analysis/Charts/Uber_Sat2014.png)

Here, you can note that peak times on Mondays (weekdays) are different from Saturdays (weekends). There is a peak in the evenings on weekends and near work hours on weekdays.
