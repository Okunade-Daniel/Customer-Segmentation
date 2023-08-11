# Customer-Segmentation
Customer segmentation is the process of dividing customers into groups based on their characteristics, behaviors, and preferences. It can help businesses understand their customers better, tailor their marketing strategies, and improve customer loyalty and retention. This project aims to segment customers into groups based on common characteristics so that the company can market to each group effectively and appropriately.

# Project Goal
The goal of this project is to analyze the available data to provide an actionable recommendation for the executive team as well as the marketing team. Specifically, this project aims to :
- Identify the most common characteristics of the customers?
- Identify the optimal number of clusters?
- Identify the differences between the clusters?
- Identify the similarities between the clusters?
- 
# Data Source
The data source for this project is the publicly available wholesale customer dataset. It contains transactions occurring between 440 customers in a wholesaling outlet.
The data set has 8 variables:
- Channel: Nominal.
- Region: Nominal.
- Fresh: Numeric.
- Frozen: Numeric.
- Grocery: Numeric.
- Milk: Numeric.
- Detergents Paper: Numeric.
- Delicassen: Numeric.

# Methodology
The methodology for this project consists of the following steps:
- Data cleaning: Outliers in the data were treated, the data contained no missing values, and duplicates.
- Data preprocessing and exploration: Create new features such as total amount, recency, frequency, and monetary value (RFM) for each customer. Standardize and normalize the numerical features.
- Data exploration: Perform exploratory data analysis (EDA) to understand the distribution, correlation, and summary statistics of the features. Visualize the data using histograms, boxplots, scatterplots, and heatmaps.
- Data modeling: Apply unsupervised machine learning techniques such as K-means clustering and hierarchical clustering to group the customers into clusters based on their RFM features. Determine the optimal number of clusters using metrics such as silhouette score, elbow method, and gap statistic. Compare and evaluate the results of different clustering methods.
- Data interpretation: Analyze and interpret the characteristics, differences, and similarities of each cluster. Provide insights and recommendations for business strategies based on the findings.
# Results
The results of this project are summarized below:
- The most common characteristics of the customers are:
    - They utilize Channel 1 the most.
    - They patronize Region 3 store more than any other Region.
    - They spend more on Fresh products than any other product category.
-. The optimal number of clusters is 3 based on the elbow method. The clusters are then named based on the product they spend the most on. Segment 0 is named Grocery Buyers, Segment 1 is named Fresh Food Buyers and Segment 2 is named Budget Buyers.
-. The differences between the clusters are:
    - They differ in their product and channel preferences given the amount they spend on average on them. Grocery Buyers spend more on Channel 2 for all their products except Delicassen which they prefer Channel 1 for. Fresh Food Buyers spend more on Channel 2 for all their products except Frozen and Milk products. Except for Frozen and Delicassen products which Segment 2 likes Channel 1 for, they prefer Channel 2 for other types of products.
    - The segments have different patterns of spending across products. For example, Grocery Buyers are the overall highest spender on Grocery, Milk, and Detergent paper. Fresh Food Buyers spend more on Fresh, Frozen and, Delicassen products. Segment 2 was not the overall highest spender in any product category.
    - They have different spending patterns across regions. Grocery Buyers spend more in Region 1, Fresh Food Buyers spend more in Region -, while Budget Buyers spend more on Region 2 than any other region.
   
-. The similarities between the clusters are
    - They spend more on channel 2 than any other channel.
    - They all patronize the Region 3 store more.
    - They all favor Channel 2 more for Groceries and Detergent Paper

a copy of the Report is  shown [here](https://www.example.com).

# Recommendations
To Executives:
1. Marketing efforts for Channel 2 should be improved across all customer segments and regions by offering a promotional package to encourage customers to use it more often.

2. Regional optimization should be invested in to improve customer experience and sales in each region customer spends more on.

3. Increased Selection of Fresh products can be employed as customers spend more on Fresh products.

To Marketing Team:
1. Target marketing strategy should be employed as the segments have different preferences for products and channels. For example, Grocery Buyers could be tageted with promotions and discounts on Grocery, Milk and Detergent Paper products through Channel 2, as they are the most likely to purchase these items from this channel.

2. Regional optimization strategy should be implemented. Product Placement strategy should also be implemented within each region to further increase market share in specific regions.

3. Channel Optimization strategy should also be implemented to  to improve the customer experience,  and boost revenue for each Channels.
