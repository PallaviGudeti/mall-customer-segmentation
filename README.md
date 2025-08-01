**Mall Customer Segmentation using K-Means Clustering**

This project applies unsupervised machine learning (K-Means Clustering) to segment customers of a mall based on their annual income and spending score to help businesses create targeted marketing strategies.

**Objective:** To identify distinct customer groups based on Annual Income and Spending Score.
**Techniques Used:** K-Means Clustering, Elbow Method, Data Preprocessing (Scaling), Visualization (Seaborn,Matplotlib).
**Tools Used:** Python, Kaggle, Pandas, Matplotlib, Seaborn, Power BI.

**Dataset:**
The dataset contains information about 200 mall customers.

**Columns - Description :**
- CustomerID - Unique customer ID
- Gender - Male/Female 
- Age - Age of the customer 
- Annual Income (k$) - Income in thousands of dollars 
- Spending Score (1-100) - Score assigned by the mall based on behavior                   

**Key steps:**
- Cleaned and preprocessed the dataset.
- Performed EDA using histograms,scatter plots,and pair plots.
- Scaled features and used Elbow method to find the optimal number of clusters.
- Applied K-Means clustering (k=5) and assigned labels to each customer.
- Visualized Clusters using scatter plots.
- Analyzed cluster profiles and extracted business insights.

**Results:**

Identified 5 customer segments:
- High-income, high-spending (ideal for premium offers)
- Low-income, high-spending (price-conscious impulse buyers)
- High-income, low-spending (upsell potential)
- Low-income, low-spending (targeted with discounts)
- Moderate-income, average spenders (Loyal and stable customers)


**Segment Summary:**

**1)Cluster 0 - Careful Big Earners:** High income but low spending.Consider premium loyalty programs or targeted ads.

**2)Cluster 1 - Mature Average Shoppers:** Older adults with stable spending.Retain via loyalty schemes.

**3)Cluster 2 - Young Impulse Buyers:** Low income, high spending youth.Target with trend-based and budget campaigns.

**4)Cluster 3 - Low Value Segment:** Low income and low spending.Minimal marketing focus.

**5)Cluster 4 - Premium Customers:** High income and high spending.VIP treatment, personalized experiences recommended.



**Business Insights:**

- Segment-based marketing is more effective than general strategies.
  
- Target Clusters 2 and 4 for immediate sales growth.
  
- Focus on converting Cluster 0 with personalized offers.
  
- Use Cluster 1 for steady revenue and retention programs.

- Minimize marketing cost on Cluster 3.


**Exploratory Data Analysis & Clustering:**

The notebook performs the following steps:
- Exploratory Data Analysis (EDA)
- Data Preprocessing & Normalization
- Elbow Method to choose optimal K
- K-Means Clustering implementation
- Cluster Visualization using 2D plots

**View the full notebook:**
https://www.kaggle.com/code/gpallavi13/mall-customer-segmentation-using-k-means

**Power BI Dashboard**
The dataset was also visualized using Power BI to explore:
- Gender distribution
- Annual Income distribution by Gender
- Spending score distribution by Gender

**Power BI file:** https://app.powerbi.com/links/-KJYMVljma?ctid=ff335ba2-bb68-489a-bbdd-f49ab4319838&pbi_source=linkShare
