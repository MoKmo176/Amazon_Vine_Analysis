# Amazon_Vine_Analysis

## Overview of Amazon Vine Analysis

### Purpose
The purpose of this analysis is to use an AWS RDS to create data visulizations on Amazon Reviews in the Electronics category. The Python and SQL functions filter the data for trend analysis with Data Frame functions that reference and organize the data on Electronics.  Count functions are used to reference records on reviews by Total Reviews, Unpaid Reviews, Paid Reviews, and further filtered by 5-Star Reviews. 

## Results

Q: How many Vine reviews and non-Vine reviews were there?
A: Total Vine reviews : 1080
   Total non-Vine reviews: 49659

![Vine Reviews](https://github.com/MoKmo176/Amazon_Vine_Analysis/blob/f17d1bec1ad81b4e2d43c464e84da10fe0b05414/Challenge16_Pics/Screenshot%202021-12-12%20at%209.14.12%20PM.png)

Q: How many Vine reviews were 5 stars? 
A: 23488

![Vine Reviews](https://github.com/MoKmo176/Amazon_Vine_Analysis/blob/f17d1bec1ad81b4e2d43c464e84da10fe0b05414/Challenge16_Pics/Screenshot%202021-12-12%20at%209.14.21%20PM.png)

Q: How many non-Vine reviews were 5 stars?
A: 454

![Non-Vines](https://github.com/MoKmo176/Amazon_Vine_Analysis/blob/f17d1bec1ad81b4e2d43c464e84da10fe0b05414/Challenge16_Pics/Screenshot%202021-12-12%20at%209.11.31%20PM.png)

Q: What percentage of Vine reviews were 5 stars? 
A: 42.037%

![Vine](https://github.com/MoKmo176/Amazon_Vine_Analysis/blob/f17d1bec1ad81b4e2d43c464e84da10fe0b05414/Challenge16_Pics/Screenshot%202021-12-12%20at%209.49.17%20PM.png)

Q: What percentage of non-Vine reviews were 5 stars?
A: 53.616%

![non-Vine](https://github.com/MoKmo176/Amazon_Vine_Analysis/blob/f17d1bec1ad81b4e2d43c464e84da10fe0b05414/Challenge16_Pics/Screenshot%202021-12-12%20at%209.49.43%20PM.png)


## Analysis Summary


There is no positivity bias based on the reviews in the Vine program. The only Vine program purchase in the the following dataframe is 5-stars, although the percentage of non-Vine 5-star reviews are higher. Vine program 5-star reviews are less than 5% of all 5-star reviews. I would analyze the 4-star review category and coompare it with the 5-star reviews in order to delineate a pattern. 

![50% Helpful](https://github.com/MoKmo176/Amazon_Vine_Analysis/blob/f17d1bec1ad81b4e2d43c464e84da10fe0b05414/Challenge16_Pics/Screenshot%202021-12-12%20at%209.48.48%20PM.png)

