# Amazon_Vine_Analysis
## Overview
Using PySpark, this analysis performs an ETL process to calculate different metrics regarding Amazon Vine reviews in the US for video games.
This analysis also investigates whether there is a bias towards favorable reviews from paid members.

## Resources
- Data Source: [Amazon Review Datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt), [Video Game Reviews Dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz)
- Software: Google Colab, PostgreSQL, pgAdmin4, AWS

## Results
### Total Number of Reviews
- Vine reviews
  - ![image](https://user-images.githubusercontent.com/83254435/130389192-209c8f59-5b2c-411c-a907-f211c90c86d1.png)

- Non-Vine reviews
  - ![image](https://user-images.githubusercontent.com/83254435/130389230-7d3eb5f1-37c9-49a4-ad5f-095163d2c38e.png)

### Total Number of 5 Star Reviews
- Vine reviews
  - ![image](https://user-images.githubusercontent.com/83254435/130389294-3d6aa733-04f5-4c6b-966c-10ba5c9f09ad.png)

- Non-Vine reviews
  - ![image](https://user-images.githubusercontent.com/83254435/130389325-8a386d14-14b6-4c29-8a36-5e8ed40eb5d0.png)

### Percentage of 5 Star Reviews
- Vine reviews
  - ![image](https://user-images.githubusercontent.com/83254435/130389357-6e7cad37-f69e-47c1-a583-b0a613e7b188.png)

- Non-Vine reviews
  - ![image](https://user-images.githubusercontent.com/83254435/130389378-c2a10fec-3d7e-436f-9157-8a445ccc0754.png)

## Summary
51% of the Vine Program's reviews were 5 stars. Only approximately 39% of Non-Vine reviews were 5 stars. This suggests a positivity bias in reviews from paid users.
Comparative analysis with paid vs unpaid reviews for specific listed game titles within the dataset could provide a more concrete illustration of bias.
