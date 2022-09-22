# Amazon_Vine_Analysis

## Overview & Purpose

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. Analysis of Amazon reviews written by members of the paid Amazon Vine program using PySpark and performed the ETL process to extract video game dataset, transformed the data, connected to an AWS RDS instance, and loaded the transformed data into pgAdmin. Then used PySpark to determine if there was any bias toward favorable reviews from Vine member in the video game dataset.  

## Results 

- How many Vine reviews and non-Vine reviews were there?

There are 94 Vine reviews and there are 4,0471 non-Vine reviews 

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There are 48 Vine 5 star reviews and there are 1,5663 non_Vine 5 star reviews. 

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

51% of Vine reviews were 5 stars and 39% of non-Vine reviews were 5 stars. 

Paid Summary

![Paid_Summary](https://github.com/xanderbilt23/Amazon_Vine_Analysis/blob/main/images/paid_summary%20.png)

Unpaid Summary

![Unpaid_Summary](https://github.com/xanderbilt23/Amazon_Vine_Analysis/blob/main/images/unpaid_summary%20.png)

## Summary

There could possibly be positivity bias for reviews in the Vine program as over half of the reviews are 5 star reviews and non-Vine reviews only 39% were 5 stars. One additional analysis that could be conducted with the dataset is a summary of the statistics for the star rating for both reviews (mean, median, & mode).
