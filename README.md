# Amazon_Vine_Analysis

## Overview 
The overview of this is to look at the data and check out the review stats. A lot of reviews had to be made by people who belong to the Amazon Vine Program. This involves people who are given a bunch of products to review and the amount of 5-star reviews may surprise you. 1st we need to perform ETL on the data to make it easier for us to read the information and put them into tables using PGAdmin/SQL.  After this is completed, we will then determine Bias of Vine Reviews by using Pandas in order to read in the data and transform it into results.

## Results
1st we needed to create a data frame where the total amount of votes is over 20 to ensure there are no errors later on but this also gives us a look at some of the products that have been voted on. After breaking this down we need to look at how many vine reviews and non-vine reviews there are. 

![image](https://user-images.githubusercontent.com/92553694/153785284-aa4dabe5-0980-4055-a858-707909a55915.png)

After breaking down how many vine views there are it is shown that there are 40,471 non vine viewers and only a small amount of 94 vine viewers. Within these reviews we also took a look at how many 5-star reviews were given out.

![image](https://user-images.githubusercontent.com/92553694/153785559-be7079d8-4475-42f7-9c3b-27c91a5df95a.png)


looking at the picture above we can see that with the paid vine review there was only a small amount with 48 and the non-vine reviews are 15,663. The percentage of vine reviews that have 5 stars are roughly 51% and the non-vine reviews are 38%. 

![image](https://user-images.githubusercontent.com/92553694/153787239-cb0c828b-1f50-478f-bbcf-321437fe59ea.png)


## Summary
This data sort of suggests that there is a bias toward five-star reviews from paid-reviewers. The reason for this is because while the majority of reviews and amount of five-star reviews are in favor of non-vine members. It still shows that more than half of vine members reviews are 5 stars. This shows a bias that paid viewers have. A way to have made this unbiased would have been further analysis with more samples and possibly adding 3 & 4-star reviews.
