# Analyzing 10Gb of Yelp Reviews Data: Graam Liu Project 2

Yelp's user, business, and reviews data were analyzed using a Spark cluster created in AWS EMR. The original data can be found in [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset) 

## Analysis

Yelp's data was uploaded to a S3 bucket and then loaded into a jupyter notebook using pyspark and analyzed using relevant libraries such as matplotlib and pandas. Findings included that restaurants are the top category by business and that written Yelp reviews tend to be negative. In addition, it was found that elite reviews are somewhat reliable for how other non-elite users might rate an experience. Additional research was also done to conclude that Yelp reviewers do not get more cynical or pessimistic as they increase their number of reviews.  

## Cluster and Notebook Configs

![notebook_configuration](assets/notebook_configuration.png)
![cluster_configuration](assets/cluster_configuration.png)
