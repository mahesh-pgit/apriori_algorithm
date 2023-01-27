Apriori Algorithm: It is the Algorithm in which Association rules are associated, lets understand what association rules are.

What is Association Rule Learning ?
Association Rule Learning has the most popular applications of Machine Learning in business. It has been widely used to understand and test various business and
marketing strategies to increase sales and productivity by various organisations including supermaket chains and online marketplaces.

Association rule learning is rule-based learning for identifying the association between different variables in a database. One of the best and most popular example
of Association rule Learning is the Market Basket Analysis. This problem analyses the association between various items that has the highest probability of being
bought together by a customer.

For example, the association rule, {onions,chicken masala} => {chicken} says that a person who has got both onions and chicken masala in his or her basket has high
probability of buying chicken also.


Apriori Algorithm: Apriori Algorithm finds the most frequent itemsets or elements in a transaction database and identifies association rules between the items just
like the above example we have mentioned. The algorithm uses a "bottom-up" approach, where frequent subsets are extended one item at once and groups of candidates are
tested against the data. The algorithm terminates when no further successful rules can be derived from the data.


How Apriori Works ?
To construct association rules between elements or items, the algorithm considers 3 important factors which are Support, Confidence and Lift.

Support: The Support of item I is defined as the ratio between the number of transactions containing the item I by total number of transactions expressed as:
             Support (I) = Number of Transactions Containing I / Total Number of Transactions

Confidence: This is measured by the proportion of transactions with item I1, in which item I2 also appears. The Confidence between two items I1 and I2, in a transaction
is defined as the total number of transactions containing both items I1 and I2 divided by the total number of transactions containing I1.
             Confidence(I1->I2) = Number of Transactions containing items I1 and I2 / Total Number of trasnactions containing I1

Lift: Lift is defined as ratio between the Confidence and Support and is expressed as:
             Lift(I1->I2) = confidence(I1->I2) / support(I2)
