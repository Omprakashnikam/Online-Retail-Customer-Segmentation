# Online-Retail-Customer-Segmentation


#Problem Statement-

In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

#Conclusion-

1.From RFM analysis, we manually creaed three clusters on a quartile basis as high, average and low value customers.

2.Most of the customers are from united kingdom and The most demanding 5 product are WORLD WAR 2 GLIDERS ASSTD DESIGNS, JUMBO BAG RED RETROSPOT, ASSORTED COLOUR BIRD ORNAMENT, WHITE HANGING HEART T-LIGHT HOLDER, PACK OF 72 RETROSPOT CAKE CASES respectively.

3.In K-means clustering, using the elbow method we got the optimal value of clusters as 2. Also, the best silhouette score obtained is when the number of clusters is 2.

4.In Hierarchical clustering, the dendrogram also depicted the number of clusters as 2. We saw in Hierarchical clustering the customers were well grouped using 2 clusters.

5.DBSCAN gave us four clusters 0 and 1 the two different clusters, and -1 and -2 as the noise which was more. There are two customer clusters that have been formed as Wholesale customers and average customers.

6.From above ml model the customers are segmented into 2 groups as follow :-

Wholesale Customers - The high value customer segment as the customers in this group place the highest value orders with a very high relative frequency and also transacted most recently.

Average Customers - The average customer segment. These customers order less frequent than the wholesale customers and their orders are pretty low valued and also rarely shop.

7.We can conclude that K-means clustering and Hierarchical clustering can be used for this dataset to segment customers based on RFM analysis.
