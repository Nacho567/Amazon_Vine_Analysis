# Amazon Vine Analysis

## **Overview**

This was an analysis of paid Amazon Vine reviews, specifically if Amazon Vine members provide better reviews because they've recieved a free product. Data was filtered through PySpark, then AWS RDS, loaded into pgAdmin, and then PySpark again for the final Vine analysis.

## **Results**

![Final review numbers]()

- Vine reviews: 94
- Non-Vine reviews: 40,471

- 5 star Vine reviews: 48
- 5 star non-Vine reviews: 15,663

- Vine reviews that were 5 stars: 51.1%
- Non-Vine reviews that were 5 stars: 38.7%

## **Summary**

The results do show that there is a positivity bias in the Amazon Vine program. The program gave 5 star reviews about 13% more often than non-Vine reviews. There is a large caveat in that the total number of Vine reviews is very small compared to non-Vine reviews. This amount means that they have no real impact on the total rating of each product. If companies were to pay for more Vine reviews though, they would start to skew the numbers. A quick analysis to show that is of the 40,565 total Vine and non-Vine reviews, only 48 were paid 5 star reviews. That amounts to 0.12% of all reviews, and only 0.31% of all 5 star reviews.
