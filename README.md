Customer Segmentation with RFM

Business Problem
FLO aims to segment its customers and develop different marketing strategies based on these segments. In this project, customer behaviors were analyzed to create meaningful groups, and actions were determined for these groups.

 ataset Story
The dataset consists of past shopping data of FLO customers who made purchases via OmniChannel (both online and offline) in 2020-2021. Key variables include customer ID, shopping channels, total number of purchases, and total spending.

Data Columns:
- `master_id`: Customer ID
- `order_channel`: Shopping channel
- `last_order_channel`: Last shopping channel
- `first_order_date`: First shopping date
- `last_order_date`: Last shopping date
- `order_num_total_ever_online/offline`: Number of online/offline purchases
- `customer_value_total_ever_online/offline`: Total online/offline spending
- `interested_in_categories_12`: Categories shopped in over the past 12 months

 Tasks
 Data Understanding & Preparation:
1. The dataset was read and examined.
2. New variables were created for total purchases and spending.
3. Date formats were adjusted.
4. Distribution of shopping channels, customer counts, and average spending was analyzed.

 Calculating RFM Metrics:
1. The analysis date was set to 2021-06-01, and each customer's recency, frequency, and monetary values were calculated based on their last purchase.

 Calculating RF and RFM Scores:
1. Recency, frequency, and monetary values were scored on a scale of 1-5, creating RFM scores.

  Defining RF Scores as Segments:
1. RF scores were converted into segments. For example, a score of 51 was labeled as the "new_customers" segment.

  Action Plan:
1. RFM values of the segments were analyzed.
2. Customer profiles for special campaigns were identified and saved to a CSV file.


 Outputs and Results
Customer behaviors were analyzed by segment, and recommendations were made for specific groups. For instance:
- Loyal customers (champions, loyal_customers) were targeted for high-value products.
- Customers at risk of churn (hibernating, at_risk) were targeted with discount campaigns to retain them.
