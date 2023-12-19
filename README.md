# Customer Segmentation with RFM Analysis
In the ever-evolving landscape of business, understanding and effectively catering to the unique needs of customers is paramount. Customer segmentation, the practice of dividing a customer base into groups with similar traits, allows businesses to tailor their strategies for enhanced customer engagement and satisfaction. This project delves into the realm of customer segmentation using RFM (Recency, Frequency, Monetary) analysis—a powerful method that classifies customers based on their recent purchase behavior, frequency of transactions, and monetary value. </br>
/illustration/
## Objectives
This project is mainly aiming for two goals: </br>
* The first goal is to calculate RFM scores for each customers based on their historical purchasing data. The purpose is to analyze customer value and explore the metrics to build the clustering algorithm.
* The second goal is to segment customers into a number of cluster for the strategy development.
## Dataset Description
I used an [E-Commerce Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data) from Kaggle that contains transaction information from around 4,000 customers. </br>
## Data Exploration
[Notebook](CustomerSegment.ipynb)
Firstly, let's look at the head of the dataframe to understand data
![image](dataHead.png)
The dataframe consists of 8 variables:
* InvoiceNo: The unique identifier of each customer invoice.
* StockCode: The unique identifier of each item in stock.
* Description: The item purchased by the customer.
* Quantity: The number of each item purchased by a customer in a single invoice.
* InvoiceDate: The purchase date.
* UnitPrice: Price of one unit of each item.
* CustomerID: Unique identifier assigned to each user.
* Country: The country from where the purchase was made.

## Customer Segmentation Methods
In this project, I used **K-Means** clustering algorithm to perform customer segmentation. </br>
When building a clustering model, we need to decide how many segments we want to group the data into. This is achieved by a heuristic called **the elbow method**. </br>
![image](elbow.png)
The “elbow” of this graph is the point of inflection on the curve, and in this case is at the 4-cluster mark. This means that we will segment customers into 4 different groups.
## Result and Interpretation
![image](3DVisualization.png)
fdjfdfdf
