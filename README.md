# Market_compaign
The goal is to perform clustering to summarize customer segments.
# Context:
Customer Personality Analysis involves a detailed examination of a company’s ideal customers. This analysis helps businesses to better understand their customer base, enabling them to tailor products according to the specific needs, behaviors, and concerns of different customer segments.
By understanding customer personalities, a company can strategically target its marketing efforts. For example, instead of marketing a new product to every customer, the company can identify the customer segment most likely to purchase the product and focus its marketing efforts on that segment.
# Attributes:
# People:

- **ID**: Customer's unique identifier.
- **Year_Birth**: Customer's birth year.
- **Education**: Customer's education level.
- **Marital_Status**: Customer's marital status.
- **Income**: Customer's yearly household income.
- **Kidhome**: Number of children in the customer's household.
- **Teenhome**: Number of teenagers in the customer's household.
- **Dt_Customer**: Date of customer's enrollment with the company.
- **Recency**: Number of days since the customer's last purchase.
- **Complain**: 1 if the customer complained in the last 2 years, 0 otherwise.

# Products:

- **MntWines**: Amount spent on wine in the last 2 years.
- **MntFruits**: Amount spent on fruits in the last 2 years.
- **MntMeatProducts**: Amount spent on meat in the last 2 years.
- **MntFishProducts**: Amount spent on fish in the last 2 years.
- **MntSweetProducts**: Amount spent on sweets in the last 2 years.
- **MntGoldProds**: Amount spent on gold in the last 2 years.

# Promotion:

- **NumDealsPurchases**: Number of purchases made with a discount.
- **AcceptedCmp1**: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise.
- **AcceptedCmp2**: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise.
- **AcceptedCmp3**: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise.
- **AcceptedCmp4**: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise.
- **AcceptedCmp5**: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise.
- **Response**: 1 if the customer accepted the offer in the last campaign, 0 otherwise.

# Place:

- **NumWebPurchases**: Number of purchases made through the company’s website.
- **NumCatalogPurchases**: Number of purchases made using a catalogue.
- **NumStorePurchases**: Number of purchases made directly in stores.
- **NumWebVisitsMonth**: Number of visits to the company’s website in the last month.

# Problem Statement:
Objective: The goal is to perform clustering to summarize customer segments.
# Results:

- Executed a comprehensive customer personality analysis to identify key customer segments and behaviors.
- Implemented Label Encoding, Standardization, and PCA to enhance data quality and optimize clustering models.
- Applied k-means clustering with WCSS and KneeLocator, identifying **3 clusters**, achieving a **Silhouette Score of 0.42**.
- Conducted Hierarchical clustering to determine **2 clusters**, resulting in a **Silhouette Score of 0.44**.
