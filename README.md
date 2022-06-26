# Amazon Vine Analysis

## Overview of the analysis of the Vine program

In this analysis, I analyzed Amazon reviews written by members of the paid Amazon Vine program. The purpose was to allow manufacturers and publishers to see reviews for their products, many of whom pay a fee to Amazon in order to provide poroducts to Vine members who purchase said products for review.

This analysis had access to ~50 datasets with product information ranging from clothing apparel to wireless products. 

Tools used:

 - AWS RDS instance
 - PySpark
 - Pandas
 - S|QL

## Results:

There is a bulleted list that addresses the three questions for unpaid and paid program reviews

Through filtiering the reviews, I narrowed to those hat were 50%+ helpful

<img width="868" alt="Screen Shot 2022-06-25 at 8 19 40 PM" src="https://user-images.githubusercontent.com/93094173/175794438-3b0bb556-7882-487f-a0b1-6d8c2d7988ee.png">

Further, I filtered the dataset to show the following calculations:

<img width="871" alt="Screen Shot 2022-06-25 at 8 20 33 PM" src="https://user-images.githubusercontent.com/93094173/175794451-5767feae-6627-4caf-860d-dad2713f1479.png">

I found that of the 51,123 reviews within the data set, 50,516 (98.8%) were unpaid and 607 (1.19%) were paid.

<img width="823" alt="Screen Shot 2022-06-25 at 8 21 06 PM" src="https://user-images.githubusercontent.com/93094173/175794484-0ff37586-0d21-41ab-804e-f0ca38d3cdf8.png">

Further, of the 607 paid reviews, only 257 (42%) were 5 star reviews.
<img width="818" alt="Screen Shot 2022-06-25 at 8 22 07 PM" src="https://user-images.githubusercontent.com/93094173/175794480-91a3e3e7-cefe-4429-a70d-ec5130d56bd9.png">


## Summary:

In sum, I would summize that of the reviewers who are Vine reviewers there isn't a bias towards 5-star reviews, but rather, they are more honest and forthright in their feedback of respetive products. Perhaps future analysis could include analyzing both paid and unpaid reviews.
