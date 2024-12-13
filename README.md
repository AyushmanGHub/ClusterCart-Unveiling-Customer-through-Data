# ClusterCart-Unveiling-Customer-through-Data

## <span style="color: #4A90E2">Introduction</span>
<hr style="border: 1px solid Grey;"/>
In this project, we aim to segment customers based on their purchasing behavior using the K-Means clustering algorithm. Customer segmentation is a critical strategy for businesses to better understand their clientele, identify distinct groups, and personalize marketing and sales strategies. By uncovering patterns within customer data, businesses can enhance customer satisfaction, improve product recommendations, and boost overall profitability.  
To accomplish this task, we utilized the following approach:  
1. **Data Analysis:** leveraged Pandas for efficient data cleaning, preprocessing, and exploratory analysis to ensure the dataset was ready for clustering.  
2. **Clustering Algorithm:** K-Means, a robust and widely used clustering technique, was implemented to group customers into meaningful clusters based on their behavioral or demographic similarities.  
3. **Dimensionality Reduction:** Principal Component Analysis (PCA) was applied to reduce the dimensionality of the data, making it easier to visualize and interpret the clusters without losing critical information.  
4. **Visualization:** Advanced visualization tools such as Plotly were employed to create dynamic and interactive plots for analyzing the clusters and providing a clear understanding of the segmentation results.  

The primary goal of this project was to identify customer groups that share similar characteristics. These insights can empower businesses to target specific segments with tailored marketing campaigns, optimize product offerings, and improve customer retention strategies. By integrating K-Means clustering with data analysis and visualization, this project demonstrates the power of data-driven customer segmentation in modern business strategies.  

## <span style="color: #4A90E2">About the Dataset</span>
<hr style="border: 1px solid Grey;"/>
The dataset used in this project, titled **Online Retail**, is publicly available from the UCI Machine Learning Repository. It contains transactional data from an e-commerce business that operates in the United Kingdom. The data provides a detailed record of customer purchases, offering valuable insights into purchasing behavior. You can refer dataset to its source on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail). 

### Figure 01.Visualization of dataset by reduceding to 2 Dimension
<img src="plots/01.png" alt="Alt Text" width="800" height ="450"/>

### Figure 02. Visualization of dataset by reduceding to 3 Dimension
<img src="plots/02.png" alt="Alt Text" width="800" height ="400"/>

### Figure 03. Distribution of number of customer from each Country
<img src="plots/03.png" alt="Alt Text" width="800" height ="450"/>

### Figure 04. Distribution of top 50 StockID
<img src="plots/04.png" alt="Alt Text" width="800" height ="400"/>

### Figure 05. Distribution of number of Customer in each KMeans Cluster
<img src="plots/05.png" alt="Alt Text" width="800" height ="450"/>

### Figure 06. Plot of Customer ID coloured by Custer in 3 Dimension
<img src="plots/06.png" alt="Alt Text" width="800" height ="400"/>


## ---------- sales strategies ----------
The probabilities for each customer show the likelihood that they will buy a specific product, based on their purchasing behavior and the cluster they belong to. Higher probabilities mean a greater chance of purchase. By examining these probabilities, businesses can identify which products are likely to be bought by customers in each segment. This insight enables businesses to create **targeted marketing strategies**, offering personalized recommendations that are more relevant to each customer, ultimately enhancing engagement and increasing the chances of successful sales.

### Likelihood (Probability) of buying for Each Product by KMeans Cluster
| Cluster | li_10002 | li_10080 | li_10120 | li_10125 | li_10133 | li_10135 | ---------------------- |
|---------|----------|----------|----------|----------|----------|----------|------------------------|
|    0    | 0.139685 | 0.141657 | 0.137839 | 0.126015 | 0.210436 | 0.177199 |   .................    |
|    1    | 0.137232 | 0.151795 | 0.151451 | 0.143733 | 0.192380 | 0.143863 |   .................    |
|    2    | 0.229921 | 0.138599 | 0.139947 | 0.265539 | 0.099843 | 0.170536 |   .................    |
|    3    | 0.121622 | 0.141712 | 0.136979 | 0.113994 | 0.129293 | 0.119751 |   .................    |
|    4    | 0.127115 | 0.145695 | 0.151906 | 0.114521 | 0.137853 | 0.102529 |   .................    |
|    5    | 0.122714 | 0.136104 | 0.136744 | 0.121490 | 0.101894 | 0.165568 |   .................    |
|    6    | 0.121711 | 0.144439 | 0.145134 | 0.114709 | 0.128302 | 0.120555 |   .................    |


## <span style="color: #4A90E2">Results and Conclusion</span>
<hr style="border: 1px solid Grey;"/>
The K-Means clustering algorithm was successfully applied to segment customers based on their purchasing behavior and demographic information. The model identified several distinct customer groups, with each cluster representing customers with similar purchasing patterns. By examining the mean probability for each product across different clusters, we were able to determine the likelihood of a customer purchasing specific items. Higher probabilities for certain products indicated that customers in those clusters were more likely to purchase them, providing actionable insights into customer preferences.

# ----------------------------------------------------------------
### * If want to know more about this project there are python Notebook file, Project report paper and all other resources included in same repository.
### * Feel free to reach out, I'm open to engaging in meaningful conversations and exchanging ideas on these areas. I welcome the chance to explore new insights, collaborate on projects, and contribute to ongoing discussions in these fields.
