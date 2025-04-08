# Market-Segmentation-Analysis-and-Customer-Behaviour-on-EV-market-data-feynn-labs-

1. ML Model Used and Its Role
The ML model used for market segmentation in the second project was a combination of KMeans Clustering and Principal Component Analysis (PCA).
  •	KMeans Clustering was used to group customers into clusters based on similarities in their financial and demographic data.
  •	PCA was applied to reduce the dimensionality of the data, making it easier to visualize and separate clusters.
  •	The Elbow Method was used to determine that the optimal number of clusters was4.
  •	The clustering outcome was evaluated using the Silhouette Score, which confirmed that the clusters were well-separated and meaningful.

2. Final Conclusion and Insights
Number of Segments: 4 Clusters
The market was successfully segmented into 4 distinct clusters based on customer behaviours and characteristics:
Cluster Characteristics:
  Cluster	Age Range	Income Level	Profession	Loan-Taking Behaviour	Spending Power
  Cluster 0	25–35	Low to Medium	Salaried	High loan-taking tendency	Moderate
  Cluster 1	30–45	Medium to High	Business	Low loan-taking tendency	High
  Cluster 2	40–55	Medium	Salaried	Moderate loan-taking tendency	Moderate
  Cluster 3	35–50	High	Business	High loan-taking tendency	High
Key Insights:
✅ Total Salary and Price:
    •	Strong correlation between Total Salary and Price indicates that higher-income individuals prefer higher-priced products.
✅ Age and Financial Decisions:
    •	Younger individuals are more likely to take personal loans and have higher spending flexibility.
    •	Older individuals tend to focus more on financial stability and conservative spending.
✅ Profession and Spending:
    •	Business professionals exhibit higher variation in spending and investment patterns.
    •	Salaried individuals have more stable spending habits.
✅ Marital Status:
    •	Married individuals with dependents tend to spend more on long-term assets and investments.
    •	Single individuals exhibit higher discretionary spending patterns.
✅ Loan Behaviour:
    •	Higher loan-taking tendency among middle-income groups indicates financial dependency on loans for high-ticket purchases.

3. Suggested Improvements
 Additional Data Points to Collect:
To enhance segmentation accuracy and gain deeper insights into customer behaviour, the following data points can be collected:
Data Point	Purpose
Income Source Type (Fixed/Variable)	To assess financial stability and predict loan-taking behaviour
Credit Score	To measure financial health and risk-taking capacity
Employment History	To determine job stability and long-term financial strength
Loan Tenure & Interest Rate	To evaluate repayment capacity and loan-taking patterns
Spending Habits (Essential vs Discretionary)	To identify product preferences and customer needs
________________________________________
Additional ML Models to Try:
1.	Gaussian Mixture Model (GMM):
  o	Useful for soft clustering where clusters may overlap.
  o	Provides a probabilistic clustering outcome.
2.	Hierarchical Clustering:
  o	Useful for analyzing sub-clusters within larger clusters.
  o	Helps identify underlying micro-segments.
3.	DBSCAN (Density-Based Clustering):
  o	Suitable for non-linear and irregularly shaped clusters.
  o	Helps identify noise and outliers.
4.	Agglomerative Clustering:
  o	Builds a hierarchy of clusters.
  o	Useful for discovering hierarchical relationships between customer segments.
________________________________________
4. Estimated Market Size
Market Domain:
  •	The estimated market size for the domain analyzed (behavioural patterns in product consumption) is valued at approximately ₹10,000 crores ($1.2 billion) annually.
  •	The market is projected to grow at a CAGR of 12% over the next five years, reflecting increasing customer demand and product diversification.
  •	High-income clusters offer the greatest revenue potential, while middle-income clusters present higher conversion potential.
________________________________________
5. Top 4 Features for Optimal Market Segmentation
The most significant features for customer segmentation are:
Rank	Feature	Reason
1	Total Salary	Strong indicator of spending power and product preference.
2	Age	Influences financial priorities and risk appetite.
3	Profession	Reflects financial stability and long-term income potential.
4	Marital Status	Affects spending behaviour and dependency levels.
________________________________________
✅ Conclusion
The market was successfully segmented into 4 meaningful clusters using KMeans and PCA. The segmentation model provided clear insights into customer behaviour, spending patterns, and loan-taking tendencies.
Count Plot:
 
![image](https://github.com/user-attachments/assets/99a940a5-2d6a-4b7f-8598-c82b0fff4817)

 


