# Amazon_Vine_Analysis

## Project Overview

The main task in this project is to analyze Amazon rAmazon Vine program and submit an analysis to the stakeholders. The analysis will determine whether or not there is any bias towards favorable reviews from Vine members in the dataset. THis will be done using PySpark to perfrom the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.

The dataset of Amazon reviews I analyzed were those in the "Music" category:

- [Amazon Reviews Dataset for Music]("https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Music_v1_00.tsv.gz")

## Results

|       | Paid | Unpaid    |
| :---        |    :----:   |          ---: |
| **Total # of Reviews**     | 7       | 105,979   |
| **# of 5-Star Reviews**  | 0        | 67,500      |
| **% of 5-Star Reviews**  | 0%        | 63.8%     |

Paid Reviews
![Paid Vine Reviews](paid%20vine%20reviews.png)

Unpaid Reviews
![Unpaid Reviews](unpaid%20vine%20reviews.png)
