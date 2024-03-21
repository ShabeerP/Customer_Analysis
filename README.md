***Customer Analysis***
**Overview**
This project investigates customer data for a store. Its primary goals are:

*Customer Segmentation*: Cluster customers into distinct groups based on demographical patterns.
*Campaign Responsiveness*: Build a predictive model to identify customers likely to respond positively to marketing campaigns.
**Dataset**
Data Dictionary:
People
● ID: Customer's unique identifier
● Year_Birth: Customer's birth year
● Education: Customer's education level
● Marital_Status: Customer's marital status
● Income: Customer's yearly household income
● Kidhome: Number of children in the customer's household
● Teenhome: Number of teenagers in customer's household
● Dt_Customer: Date of customer's enrollment with the company
● Recency: Number of days since customer's last purchase
● Complain: 1 if the customer complained in the last 2 years, 0 otherwise
Products
● MntFruits: Amount spent on fruits in last 2 years
● MntMeatProducts: Amount spent on meat in last 2 years
● MntFishProducts: Amount spent on fish in last 2 years
● MntSweetProducts: Amount spent on sweets in last 2 years
● MntGoldProds: Amount spent on gold in last 2 years
Promotion
● NumDealsPurchases: Number of purchases made with a discount
● AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
● AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
● AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
● AcceptedCmp4: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
● AcceptedCmp5: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
● Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise
Place
● NumWebPurchases: Number of purchases made through the company’s website
● NumCatalogPurchases: Number of purchases made using a catalog
● NumStorePurchases: Number of purchases made directly in stores
● NumWebVisitsMonth: Number of visits to the company’s website in the last month.
**Goals**
Exploratory Data Analysis (EDA): Uncover trends, insights, and anomalies within the customer data.
Data Processing: Clean, transform, and prepare the data for modeling.
**Model Development**:
*Classification*: Employ algorithms (e.g., Logistic Regression, Decision Trees, Random Forest) to predict campaign responsiveness.
*Clustering*: Using the K-MeansClustering technique to segment customers.
*Evaluation*: Assess model performance using relevant metrics (accuracy, precision, recall, F1-score, Silhouette score).
*Visualization*: Create compelling charts to communicate findings.
**Key Insights and Findings**
Based on the evaluation metrics, the support vector machine (SVM) model performs slightly better than the logistic regression model. It has a higher recall and F1 score, indicating better performance in correctly identifying positive cases which is often crucial in marketing campaigns where correctly identifying potential customers who would accept the campaign is important.
*Next Steps and Improvements*
1. Deploy the selected SVM model into a production environment where it can be used to make predictions on new data.
2. Optimization: Explore further optimization techniques such as fine-tuning hyperparameters, feature engineering, or trying different machine learning algorithms to improve model performance further.
**Methodology**
Exploratory Data Analysis (EDA)
Univariate and multivariate analysis
Visualization techniques (histograms, scatter plots, box plots, etc.)
Data Preprocessing
Handling missing values
Feature scaling or normalization
Encoding categorical features
Modeling
*Classification*:
Logistic Regression
Decision Trees
Random Forest
Support Vector Machine
*Clustering*:
K-Means
*Evaluation*:
Classification metrics (accuracy, precision, recall, F1-score)
Clustering metrics (Silhouette score, Davies-Bouldin index)
*Visualization*
Plots to illustrate customer segments
Confusion matrix and ROC curve for classification evaluation
How to Contribute
[I will be more happy if you contribute more to this project or report any bugs, code improvements, etc.]
License
Please take a look at the license section.
