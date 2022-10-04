# Amazon_Vine_Analysis

# Overview

Vine is a program used by Amazon to incentivize customers for reviews regarding products. In this analysis, we wanted to understand if this incentive produces higher ratings on Home Improvement products compared to reviews that are unpaid for their review. 

I was able to extract, transform and load (ETL) the data from AWD RDS into Google Collab. From there I was able to load the data into PGAdmin and use SQL to query build tables and query the data. 

# Anaylsis

## Paid Reviews:

There were a total of 266 paid vine reviews.

There were a total of 125 paid 5 – star reviews.

The percentage of 5-star reviews when the review was paid for was: 46.99%


## Unpaid Reviews:

There were a total of 38,829 reviews that were not paid. 

There were a total of 18,246 non-paid 5- star reviews.

The percentage of 5- star reviews when the review was not paid was: 46.99%.



# Summary 

There seems to be no real difference if the review is incentivized by free products. There needs to be more analysis done but based on these data points, there seems to be no real advantage or bias of using the Vine program for higher reviews. 


# Additional Analysis 
An additional way to analyze the data is to compare the mean of the star rating from paid reviews compared to non-paid reviews. The mean from the paid reviews is higher than the mean for unpaid reviews:


