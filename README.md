# product_range
# Final project - Product range analysis of an online store.

We got a dataset with 541909 entries that contain information about orders made in the store: order number and date, identifier and name of the product, purchased quantity, price per unit, customer id. 

The **goal** of the research is to analyze the popularity and profitability of products, factors affecting(impacting) demand to find ways to increase sales.
* Data was preprocessed and split into two datasets to analyze orders and cancellations separately.
*  Products were categorized by price from very cheap to very expensive and by keywords in 11 categories. 
*  Were found that there are ~35% casual customers and much more loyal that made 2 and more orders.
*  Customers were categorized by average check and found that more common to make small orders.
*  We also checked if there is a tendency among loyal customers to make big orders and there is no such.
*  We analyzed the seasonality of demand and found it increasing in relation to the holidays - Easter and Christmas. 
*  Analysis of carts (using the Apriori algorithm) showed that the most common combinations of goods are similar products that differ by color or design. 
*  Products of the category 'very cheap' more than others were bought in a big quantity - 12 units per order. 
* There were quite many canceled orders - 14.35%.
* We tested two statistical hypotheses and found out that differences between average revenues from cheap and expensive products are statistically significant, and between average revenues in winter and summer aren't.

**Conclusions:**
* We had 4334 customers this year and 2829(65%) made more than 1 order so they are loyal and possibly will return in the future, we need to attract them with special promotions, emails, exclusive offers for buying the same products, etc.
* We have a very perspective category of ‘very cheap’ products with prices 0.04-2.12, we sold 280011 such units, we can increase these sales by adding more similar goods and special offers for orders in big amount. Products of the category ‘very expensive’ should be checked, maybe the most expensive ones less suitable for our store or we oppositely should expand this category.
* We had significant peaks of demand in Easter and Christmas because we sell a lot of stuff for holidays. We can make a sale with special offers in these periods, we can add more goods related to parties and specific holidays to even increase these peaks.
* The amount and sums of canceled orders are not crucial, but still, we can reduce it by checking the possible reasons and if it depends on us - fix it.
