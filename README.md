# Amazon_Vine_Analysis
## Overview
The purpose of this analysis was to analyze Amazon product reviews written by members of the paid Amazon Vine program. The Amazon Vine program provides a small fee to Amazon customers to leave written product reviews on the Amazon website. In this case, an analysis was conducted on reviews of pet products. Data was extracted and transformed using PySpark and Google Colab. The data was then loaded into pgAdmin via a AWS RDS instance. 

## Results
An anlysis was conducted to determine whether there is any bias towards reviews that were written as part of the Vine program. The number of 5-star rated pet product reviews was calculated for participants and non-participants in the Vine Program. 
- Of the 380,010 Amazon review for pet products, 170 were written by individuals participating in the Vine Program while 37,840 were written by non-Vine Program customers.
- 65 product reviews written by Vine Program participants were given a 5-star rating. 20,612 product reviews written by Amazon customers who were not participants in the Vine Program included a 5-star rating.
- Overall, 38.2% of reviews written by participants in the Vine Program were given a 5-star rating while 54.5% of product reviews written by non-participants were given a 5-star rating. 

## Summary
The data indicates that participants in the Vine Program were much less likely than non-partcipants to give a pet product a 5-star review. It's possible that Vine Program reviewers gave lengthier, more nuanced and thorough reviews than non-particpants, and were therefore more discerning with their 5-star designations. In a future analysis, I would like to compare the length of reviews written by participants and non-participants of the Vine Program. 
