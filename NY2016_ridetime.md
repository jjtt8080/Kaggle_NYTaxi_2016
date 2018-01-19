New York Taxi Ride Time Prediction
================

Executative Summary : New York Taxi Trip Time Prediction
========================================================

The dataset is obtained from the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published by the NYC Taxi and Limousine Commission (TLC). This report will be demostrating on the taxi trip time prediction for the following predictors : Pickup location, Drop Of Location, Pickup timeframe during the date.

Exploratory Data Analysis
-------------------------

We have done some exploratory data analysis in the previous assignment in page <a href="https://jjtt8080.neocities.org/Data%20Science%20Projects/New%20York%20Taxi%202016/ny_taxi_popular_pickup.html"> New York Taxi Popular Pickup Location Map</a>.

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Including Plots
---------------

You can also embed plots, for example:

![](NY2016_ridetime_files/figure-markdown_github-ascii_identifiers/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
