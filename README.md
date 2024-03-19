# Product-sale-analysis
## Objective:

The objective of the data validation process was to ensure the accuracy, completeness, and integrity of the dataset containing 15,000 rows and 8 columns. This validation aimed to prepare the data for in-depth analysis and derive actionable insights for optimizing sales strategies and revenue generation for Pens and Printers' new product line.
The data validation process involved cleaning a dataset initially containing 15,000 rows and 8 columns. The cleaning steps included addressing non-unique values, missing data, outliers, and ensuring data integrity across various columns.

The 'week' column required no cleaning, as it had the expected values.
In the 'sales_method' column, non-unique values were consolidated, resulting in three distinct sales methods: 'Call + Email,' 'Call,' and 'Email.'
The 'customer_id' column had no missing values and contained 15,000 unique IDs.
'nb_sold' and 'nb_site_visits' columns had numeric values without missing entries.
The 'revenue' column had missing values, which were addressed by removing affected rows.
Outliers in the 'years_as_customer' column were removed for data integrity.
After cleaning, the dataset had 13,924 rows and 8 columns.

## Insights and Recommendations:

Customer Engagement: "Email" method had the highest sales transactions (6,922), followed by "Call" (4,781), and "Email + Call" (2,223).
Revenue Generation: "Email + Call" was the most lucrative method (31% of total revenue), followed by "Email" (53%), while "Calls" contributed 18% of total revenue.
Revenue Over Time: "Email + Call" consistently led in mean revenue, followed by "Email" and then "Call."
### Recommendations:

Customer Approach: Continue using the "Email" method for effective customer engagement.
Revenue Generation: Give preference to "Email + Call" for revenue generation due to its consistent high mean revenue.
Monitoring and Adaptation: Continuously monitor market dynamics and adapt strategies as needed.
Enhance Data Collection: Prioritize completeness and validation checks for data integrity.
By implementing these recommendations, Pens and Printers can optimize their sales approaches and drive success in the market.
