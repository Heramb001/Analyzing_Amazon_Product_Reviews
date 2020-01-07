# Analyzing_Amazon_Product_Reviews
Analyzing Amazon Product Reviews and generating valuable insights(positive and negative sentiments) to build a product Recommendation engine 

### ***Importance of Online Reviews***

Many times while purchazing an item online people see the ratings, but ratings alone do not give a complete picture of the products we wish to purchase. So, as a precautionary measure, people tend to read a product’s reviews before deciding whether to buy it or not.

Online product reviews are a great source of information for consumers. From the seller's point of view, online reviews can be used to gauge the consumers’ feedback on the products or services they are selling.

### ***Problem of Fake Reviews***

Online reviews have become an important factor when people make purchase and business decisions. The increasing popularity of online reviews also stimulates the business of fake review writing, which refers to paid human writers producing deceptive reviews to influence readers’ opinions. Such fake reviews can create problems to customers who are accustomed to reading reviews before making a final purchase decision as the decisions are possibly influenced by non-consumers. This project aims to eliminate fake reviews as accurate as possible.

### ***Sentiment Analysis***

Customer satisfaction is the key to business success. it’s key for companies to pay close attention to Voice of Customer to improve the customer experience. By analyzing and getting insights from customer feedback, companies have better information to make strategic decisions, an accurate understanding of what the customer actually wants and, as a result, a better experience for the customer. To achieve this we can use the concept of sentiment analysis on the product reviews that we get as a feedback from customer.

Sentiment Analysis is the automated process of understanding the sentiment or opinion of a given text. This machine learning tool can provide insights by automatically analyzing product reviews and separating them into tags: Positive, Neutral, Negative.

### ***Recommender System***

Online stores have millions of products available in their catalogs. Finding the right product becomes difficult because of this ‘Information overload’. Users get confused and this puts a cognitive overload on the user in choosing a product.

Recommender systems help customers by suggesting probable list of products from which they can easily select the right one. They make customers aware of new and/or similar products available for purchase by providing comparable costs, features, delivery times etc.

In many ways, recommender systems were a catalyst for the current popularity of machine learning. One of Amazon's earliest successes was the "Customers who bought this, also bought..." feature, while the million dollar Netflix Prize spurred research, raised public awareness, and inspired numerous other data science competitions.


### ***About the Dataset***

The dataset contains the customer review text with accompanying metadata, consisting of three major components:

A collection of reviews written in the Amazon.com marketplace and associated metadata from 1995 until 2015. This is intended to facilitate study into the properties (and the evolution) of customer reviews potentially including how people evaluate and express their experiences with respect to products at scale. (130M+ customer reviews).

A collection of reviews that have been identified as non-compliant with respect to Amazon policies. This is intended to provide a reference dataset for research on detecting promotional or biased reviews. (several thousand customer reviews). This part of the dataset is distributed separately and is available upon request.

As the Dataset is large (~140GB), I have taken a subset of dat from a catergory 'Books, Electronics' 


Dataset URL : [Products dataset](https://jmcauley.ucsd.edu/data/amazon/index.html)



We will also try to augment this dataset with another datasets in [Products MetaData](https://jmcauley.ucsd.edu/data/amazon/index.html), [AWS Open Registory](https://s3.amazonaws.com/amazon-reviews-pds/readme.html),  to give accurate recommendations to the customer.


### ***Proposed Flow of the Model***


Data Cleaning --> Data Preprocessing --> Analyzing Reviews by Exploratory Data Analysis --> Sentiment Analysis of Reviews (Generating Good and Bad Reviews) --> Product Recommendations based on the reviews and overall score.



Building a model that tries to solve below problems
1.   Sentiment Analysis on Product reviews.
2.   Product Recommendations based on the reviews and overall score.


### ***Citiation for Dataset***

- R. He, J. McAuley. Modeling the visual evolution of fashion trends with one-class collaborative filtering. WWW, 2016
- J. McAuley, C. Targett, J. Shi, A. van den Hengel. Image-based recommendations on styles and substitutes. SIGIR, 2015
