# Applied Machine Learning in Local Supermarket

### **📁 Resources** 
> - [Paper](./sources/Local_Supermarket_Paper.pdf) <br>
> - [Presentation](./sources/Local_Supermarket_Presentation.pdf)

## Abstract
This project aims to identify the most effective rules and patterns and recommend products by adopting various data mining techniques such as TF-IDF, association rules, and recommendation systems. Also, by providing effective rules and patterns, it will be helpful for supermarkets to retain loyal customers or VIPs. In general, consumers do not just buy one item when they buy a product at a supermarket, but rather buy several types of items at the same time. Therefore, if we can find the correlation between the various types of products that consumers purchase, we can use this to prepare a useful sales strategy. In addition, if retailers know the composition of customers' shopping baskets, they can use them to prepare products or make product arrangement decisions.

## Data description
To get the data, we tried to contact with many supermarkets, and as a result, we were able to get data from one local supermarket. It is located in an apartment complexes, elementary schools and hospitals. Nearby, there are lots of competitors. From here, we were able to get about 1,000 sales data. It consists of trade name, barcode number, unit price, the number of purchasing, real price and point.

## Goal
This project intends to conduct under the following four goals.

* Goal 1: Classify product names according to item type using TF- IDF
* Goal 2: Discover the association rules between purchased products.
* Goal 3: Improve product placement based on the relationship between products.
* Goal 4: Predict future purchases and establish a product recommendation system.

## Results
### Association Rules Analysis
It shows the sales strategy based on the analysis results so far. First of all, there are four sales strategies.
1. Focus on the best-selling products and prepare enough stock for these items.
2. Display the products at 130-140cm on the floor where the eyes are focused.
3. Display the best-selling products in the back of the store to attract customers to every corner of the store.
4. Display the products that are difficult to manage inventory such as fruits and vegetables near the entrance and increase the sales rate by attracting interest.
Also, we improved the product placement. The best-selling confectionery was placed in the center, and correlated products were placed close together.
![pp](https://user-images.githubusercontent.com/93263147/210555398-783a05f5-9ec8-4891-8e57-3a0bdc417d09.png)

### Recommendation
The results of the recommendation system can be utilized as follows. First, when an item arrives in the supermarket, the boss enters the item in the POS system. Then, the program runs a recommendation algorithm based on past customer data. If a new item is likely to be preferred by a customer, each customer will receive the recommendation message. It is good for each customer to be notified about the product they want to buy, and the boss can induce the customer to act on the next purchase, which leads to making profits.
![rec](https://user-images.githubusercontent.com/93263147/210555421-85f55832-59fb-4487-9483-7727a6ee41c9.png)
