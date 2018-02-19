# Associative-learning
**Simple apriori and eclat models in python and R** 

When we go grocery shopping, we often have a standard list of things to buy. Each shopper has a distinctive list, depending on one’s needs and preferences. A housewife might buy healthy ingredients for a family dinner, while a bachelor might buy beer and chips. Understanding these buying patterns can help to increase sales in several ways. If there is a pair of items, X and Y, that are frequently bought together:

* Both X and Y can be placed on the same shelf, so that buyers of one item would be prompted to buy the other.
* Promotional discounts could be applied to just one out of the two items.
* Advertisements on X could be targeted at buyers who purchase Y.
* X and Y could be combined into a new product, such as having Y in flavors of X.

So we need some principle or an idea to optimize the sales so that there's mutual satisfaction between the customer and the shop. That is, both are happy with what they've got and that's where Associative Learning comes to play.

Association rules analysis is a technique to uncover how items are associated to each other. There are three common ways to measure association:

1. Support
2. Confidence and 
3. Lift

# Summary of dataset #

A summary of dataset that I've used is consisting of 7500 transactions and 120 different grocery items as shown below:
Transactions as item
Matrix in sparse format with
 7501 rows (elements/itemsets/transactions) and
 119 columns (items) 
 and a density of 0.03288973 meaning the sparse matrix has 3.28% of non-zero values

**most frequent items:**

mineral water          eggs     spaghetti  french fries     chocolate 
         1788          1348          1306          1282          1229 
      (Other) 
        22405 

**element (itemset/transaction) length distribution:**

sizes
   1    2    3    4    5    6    7    8    9   10   11   12   13   14   15   16   18   19   20 
1754 1358 1044  816  667  493  391  324  259  139  102   67   40   22   17    4    1    2    1 

   1  : meaning that there were 1754 baskets with only 1 product. 
1754

**some more stats**

   Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
  1.000   2.000   3.000   3.914   5.000  20.000 

includes extended item information - examples:
             labels
1           almonds
2 antioxydant juice
3         asparagus
