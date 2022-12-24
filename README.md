# Amazon_Vine_Analysis

## Purpose of Analysis

The purpose of this analysis is to analyze customer reviews written by members of the paid Amazon Vine program. We are specifically looking at 5-star reviews of given products. Through the ETL process, we are able to determine a relationship between users who are members of Amazon Vine and 5-star reviews.

For this particular analysis, data from the Pet Products V1 dataset was used and pulled from the following site: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt.

From there, the Pet Products V1 dataset was pulled into Google Colab and Spark was imported and used to do the analysis. 

<img width="794" alt="Screen Shot 2022-12-24 at 10 54 36 AM" src="https://user-images.githubusercontent.com/110838228/209443252-e10460d3-67e1-41b9-9f31-0442b5a12aa2.png">

## Results

For the analysis, I used Pandas in a Jupyter Notebook to create dataframes.

- How many Vine reviews and non-Vine reviews were there?

<img width="551" alt="Screen Shot 2022-12-24 at 10 58 11 AM" src="https://user-images.githubusercontent.com/110838228/209443336-ca193005-1860-4e75-a581-2314427f459b.png">

According to my dataframe, there were 10215 Vine reviews and 2633399 non-Vine reviews.

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

<img width="526" alt="Screen Shot 2022-12-24 at 11 29 53 AM" src="https://user-images.githubusercontent.com/110838228/209444223-cb29bc68-366f-4336-b1c2-38d0d5afae36.png">
<img width="500" alt="Screen Shot 2022-12-24 at 11 31 01 AM" src="https://user-images.githubusercontent.com/110838228/209444249-1756e96d-dbbd-4b39-938e-9b97fab9c063.png">


According to my dataframe, there were 1641210 5-star Vine reviews and 4343 non-Vine 5-star reviews.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

<img width="295" alt="Screen Shot 2022-12-24 at 11 51 27 AM" src="https://user-images.githubusercontent.com/110838228/209444820-c64fdae8-1224-4ddd-9ee0-0c24a5386d39.png">

<img width="338" alt="Screen Shot 2022-12-24 at 11 51 14 AM" src="https://user-images.githubusercontent.com/110838228/209444812-a0a43d48-bef1-49b5-95fe-e11f3fe6bf2d.png">


According to my dataset, 38.23% of Vine reviews were 5 stars, and 54.47% of non-Vine reviews were 5 stars.

## Summary

There might be a bit of positivity bias in this dataset given that almost 40% of Vine reviews got 5-stars. However, compared to almost 55% perfcent of non-Vine reviews being 5 stars, it does make sense that there are more non-Vine 5 star reviews than 5-star Vine reviews, under the assumption these reviewers are harsher.

To support this statement, we could look at verified purchase percentages against both Vine and non-Vine members. If we see that verified purchasers are giving less 5-star reviews than non-verified purchasers, that would support the statement that those who have more "weight" to their review are harsher. We could then further compare this number to both Vine and non-Vine members, and based on what those percentages tell us, we can make more conclusions about customers who have "special" review privileges. 








