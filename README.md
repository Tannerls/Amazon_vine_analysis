# Amazon_vine_analysis
##  Overview
The purpose of this analysis was to analyze Amazon reviews written by members of the paid Amazon Vine program. I chose to do my analysis over Video Game reviews using the following URL link: [Amazon Reviews US Video Games](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz).   

## Results
The results of the analysis show that the total review count for US video games was 1,785,886. After filtering the data down to reviews containing more than 20, and have a helpful count greater than 50% the total becomes 40,565. 

![total_reviews](https://user-images.githubusercontent.com/83738699/137604714-c31dc62f-a93d-47cb-a209-6699675985dc.PNG)
![filtered_reviews](https://user-images.githubusercontent.com/83738699/137604715-7ab3d420-cb7b-4ec7-a5a3-08e197438233.PNG)

Using the filtered data and then splitting it between paid and unpaid reviews you get the following results. 

![total_paid_and_5star](https://user-images.githubusercontent.com/83738699/137604817-26dce279-7e39-4aa0-a6c3-541b3fce0943.PNG)

Given this information, unpaid reviews are doing a lot more than the paid reviews. Only 48 of the five star reviews was from a paid member, this leaves us with 24,808 unpaid five star reviews. While just among the paid reviews 61.3% left a 5 star review. This is high among just the paid members, but compared to the over all number of reviews it is minor. 

## Summary
The amount of paid 5 star reviews is high, but I think we need to take a look at the products that they are testing. Given this type of information, we can see if the products them selves have a factor in the reviews being left. If they are testing higher quality items then they are more likely to leave a 5 star review.  
