# Amazon_Vine_Analysis
use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 

## Results

NOTE: Data has been filtered by droping all null values and filtering the data such that all products have a minimum of 20 votes and the helpful raiting is over 50 pecent. 

* How many Vine reviews and non-Vine reviews were there?
  * [Total number of reviews were 37475.](https://colab.research.google.com/github/StephenDini/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb#scrollTo=zJVuSNOkvo4Q&line=1&uniqifier=1)
  * [Total number of Vine Reviews were 90.](https://colab.research.google.com/github/StephenDini/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb#scrollTo=CQscKXPTwoEP&line=2&uniqifier=1)
  * [Total number of Non-Vine reviews were 37385.][https://colab.research.google.com/github/StephenDini/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb#scrollTo=wDJvgG2ayLSj&line=2&uniqifier=1]
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  * [Total number of 5 star reviews are 14670.](https://colab.research.google.com/github/StephenDini/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb#scrollTo=wDJvgG2ayLSj&line=3&uniqifier=1)
  * [Total number of 5 star Vine reviews are 44](https://colab.research.google.com/github/StephenDini/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb#scrollTo=7biC5s6Qxk5Z&line=3&uniqifier=1)
  * [Total number of 5 star Non-Vin reviews are 14626.](https://colab.research.google.com/github/StephenDini/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb#scrollTo=opiPh6h8yf4Q&line=3&uniqifier=1)
* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? 
  * [Vine is 49%](https://colab.research.google.com/github/StephenDini/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb#scrollTo=V3ZXcimax4Dj&line=2&uniqifier=1)
  * [Non-Vine is 39%](https://colab.research.google.com/github/StephenDini/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb#scrollTo=kLGi0Stgyk51&line=3&uniqifier=1)
  
## Summary

When looking at the statistics its hard to say if there is a bias. We are indeed showing that the 90 Vine reviews, of which 44 were 5 star raitings, percentages were indeed higher than that of non payed reviews. With such a small sample size it may not be best to draw conclusions just yet. The 10 percent different does streangth the assumption that paid reviews contain bias.

More data is needed or expand the filter to include 4 and 5 stars. 
