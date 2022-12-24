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

<img width="509" alt="Screen Shot 2022-12-24 at 11 03 44 AM" src="https://user-images.githubusercontent.com/110838228/209443457-523c8731-57e5-4d62-b8c1-aef986d7131c.png">

According to my dataframe, there were 1645553 five-star reviews of this product.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?






