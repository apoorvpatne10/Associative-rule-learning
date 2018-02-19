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

A summary of dataset that I've used is consisting of 7500 transactions and 120 different(in a week) grocery items as shown below:

![alt text](https://i.imgur.com/Sd3kKtc.png)

Transactions as item
Matrix in sparse format with 7501 rows (elements/itemsets/transactions), 119 columns (items) and a density of 0.03288973 meaning the sparse matrix has 3.28% of non-zero values.

(1 1754) : meaning that there were 1754 baskets with only 1 product. 
