# Instacart Market Basket Analysis

This repo shows a set of Jupyter Notebooks that I used to tackle the [Instacart Masket Basket Analysis challenge](https://www.kaggle.com/c/instacart-market-basket-analysis). The [dataset](https://github.com/khanhnamle1994/instacart-orders/tree/master/data) for this competition is a relational set of files describing customers' orders over time. The goal of the competition is to predict which products will be in a user's next order. The dataset is anonymized and contains a sample of over 3 million grocery orders from more than 200,000 Instacart users. For each user, Instacart provides between 4 and 100 of their orders, with the sequence of products purchased in each order. Instacart also provides the week and hour of day the order was placed, and a relative measure of time between orders.

Here are the different notebooks:
* [Data Exploration](https://github.com/khanhnamle1994/instacart-orders/blob/master/notebooks/Instacart-Simple-Data-Exploration.ipynb): Exploring the raw datasets.
* [Customer Segmentation](https://github.com/khanhnamle1994/instacart-orders/blob/master/notebooks/Customer-Segments-with-PCA.ipynb): Segmenting the customers with Principal Component Analysis and K-Means Clustering.
* [Association Rule Mining](https://github.com/khanhnamle1994/instacart-orders/blob/master/notebooks/Association-Rule-Mining.ipynb): Applying the Apriori algorithm to mine association rules between orders and customers.

A 3-part series of accompanied Medium blog posts have been written up and can be viewed here:
* [Part 1: Which Grocery Items Are Popular?](https://towardsdatascience.com/instacart-market-basket-analysis-part-1-which-grocery-items-are-popular-61cadbb401c8)
* [Part 2: Which Groups of Customers Are Similar?](https://towardsdatascience.com/instacart-market-basket-analysis-part-2-which-groups-of-customers-are-similar-618e88b0866d)
* [Part 3: Which Sets of Products Should Be Recommended To Shoppers?](https://towardsdatascience.com/instacart-market-basket-analysis-part-3-which-sets-of-products-should-be-recommended-to-shoppers-9651751d3cd3)

## Environment

* [Saturn Cloud](https://www.saturncloud.io/)

## Requirements

* [Python 3.6](https://www.python.org/downloads/release/python-360/)
* [Jupyter Notebook](http://jupyter.org/)

## Dependencies

Choose the latest versions of any of the dependencies below:
* [pandas](https://pandas.pydata.org/)
* [numpy](http://www.numpy.org/)
* [scipy](https://www.scipy.org/)
* [matplotlib](https://matplotlib.org/)
* [sklearn](http://scikit-learn.org/stable/)

## License

MIT. See the LICENSE file for the copyright notice.
