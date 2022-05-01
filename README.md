# Amazon_Vine_Analysis

## Overview

The purpose of this challenge was to learn more about big data and how companies handle it. The tools we used to handle a large data set were PySpark, Amazon Web Services, and PGAdmin. 

We analyzed reviews on Amazon for a certain product they sell. In this case, I analyzed watches for sale on Amazon. We checked if there was any bias for the paid service of Amazon Vine reviews. We were checking if there was any favorable bias from Vine reviews and if those paid for Vine reviews made a difference in the percentage of 5-star reviews.

# Analysis

I analyzed watch reviews for Amazon and if there was any bias from the Vine reviews. I used PySpark to perform the ETL process as well as connect the data to Amazon Web Service's RDS. After we transformed the data, we loaded it into PGAdmin. 

# Results

![Total_Vine_Reviews](https://user-images.githubusercontent.com/95515322/166130075-7515a222-f6fb-4e3c-9f40-8c17ba2184ed.png)

There were **8,390 total reviews**. Of those reviews, **47** were paid Vine reviews and **8,343** were unpaid Vine reviews.

![Total_5-star_Reviews](https://user-images.githubusercontent.com/95515322/166132485-b4313d48-3a49-414e-bc4e-be7ff8325829.png)

There were **4,333 total reviews**. Of those reviews, **15** were paid Vine reviews and **4,025** were unpaid Vine reviews.

![Percentage_5-star_Reviews](https://user-images.githubusercontent.com/95515322/166132507-09d7db59-ecd9-4361-bac2-40b317a18612.png)

There were **31.91% of paid Vine reviews were 5-star reviews.**

**0.35% of total 5-star reviews were paid Vine reviews.**

**48.24% of total unpaid reviews were unpaid 5-star reviews.**

**92.89% of total 5-star reviews were unpaid 5-star reviews.**

## Conclusion

From our analysis, it looks like 32% of total paid Vine reviews were 5-star reviews. This tells me there isn't much bias with Vine since 68% of those reviews were unpaid. Backing this claim up is our statistic that tells us 92.89% of 5-star reviews were unpaid 5-star reviews. 

If we wanted to break this down even further, we could always use an r-value and/or p-value to further bolster our hypothesis if Vine offers a bias towards Amazon reviews. 
