# Market Basket Analysis in Python using Apriori Algorithm
# Description
Algorithms that use association rules include AIS, SETM and Apriori. The Apriori algorithm is commonly cited by data scientists in research articles about market basket analysis. It identifies frequent items in the database and then evaluates their frequency as the datasets are expanded to larger sizes.
# What Is an Apriori Algorithm?
Apriori algorithm assumes that any subset of a frequent itemset must be frequent. Say, a transaction containing {wine, chips, bread} also contains {wine, bread}. So, according to the principle of Apriori, if {wine, chips, bread} is frequent, then {wine, bread} must also be frequent.
# Steps for Apriori Algorithm
* Set a minimum value for support and confidence. This means that we are only interested in finding rules for the items that have certain default existence (e.g. support) and have a minimum value for co-occurrence with other items (e.g. confidence).

* Extract all the subsets having higher value of support than minimum threshold.

* Select all the rules from the subsets with confidence value higher than minimum threshold.

* Order the rules by descending order of Lift.
# Technologies
The project is created with : 
* Libraries :
  
   I.   MLxtend
  
   II.  Pandas
  
   III. Numpy
  
   IV.  Matplotlib
# Screen Shots of Output
![output_44_0](https://github.com/sayakmaity2000/Market-Basket-Analysis/assets/137389114/74133348-ae89-4ae1-b70b-f6e3517371b5)
![output_52_0](https://github.com/sayakmaity2000/Market-Basket-Analysis/assets/137389114/430f34de-d7ee-42c6-a82b-a9019fa0798e)
![output_68_0](https://github.com/sayakmaity2000/Market-Basket-Analysis/assets/137389114/5959a1c7-f0e3-400b-967d-12ae453b153c)
![output_77_0](https://github.com/sayakmaity2000/Market-Basket-Analysis/assets/137389114/c1411a25-a28f-456e-aec6-8c8c40591d5a)
# Contributed by
Sayak Maity



