# Amazon_Vine_Analysis


## Overview of the analysis of the Vine program
Using the US pet product dataset from amazon, use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders

## Results:

* How many Vine reviews and non-Vine reviews were there?




![total-paid-reviews](https://user-images.githubusercontent.com/93004710/163743532-5941ad90-b377-4c82-b56e-0e75ac4e6234.png)





![total-unpaid-review](https://user-images.githubusercontent.com/93004710/163743548-0c387c47-8cf7-4550-89d3-7a2c3862209e.png)





* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?





![total-paid-5](https://user-images.githubusercontent.com/93004710/163743557-c424a442-a994-449c-96f0-d8a4a9889a78.png)





![total-unpaid-5](https://user-images.githubusercontent.com/93004710/163743567-b957095c-4269-480e-b5dc-d7084e41bc01.png)





* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?




![total-paid-percent](https://user-images.githubusercontent.com/93004710/163743612-81fb9777-fded-453c-a3df-bd0fb28c732a.png)





![total-unpaid-percent](https://user-images.githubusercontent.com/93004710/163743641-2f6c386e-e464-48ef-92c2-3896c5b5adb8.png)




## Summary:
There isn't any positivity bias for reviews in the Vine program. The paid results of the 5 star reviews in the vine program were roughly 39% while the unpaid 5 star reviews were roughly 54%. One additional analysis that we could do with the dataset is finding the statistical distribution.
