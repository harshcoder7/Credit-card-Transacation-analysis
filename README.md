**Credit-Card-Financial-Dashboard-PowerBI**
***

**Problem Statement:**

To develop a comprehensive credit card weekly dashboard that provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations effectively.


![image](https://github.com/user-attachments/assets/682d2c25-8bcf-4670-bf57-9b858d1b19c1)

![image](https://github.com/user-attachments/assets/d0cef07b-6820-4bdb-9e9a-1c7f6abac446)

**Description:**
The dataset contains 10,108 records with 18 columns, primarily related to credit card transactions and customer profiles. Here's a summary of key insights, correlating the data with the provided Power BI dashboard:
***

**Key Attributes from the Dataset:**

Card Categories: The dataset includes various card categories like Blue, Silver, Gold, and Platinum, aligning with the dashboard's "Card Category Performance" analysis.

Revenue and Interest: Data for Total_Trans_Amt, Interest_Earned, and Credit_Limit can be linked to total revenue, interest earned, and transaction amount breakdowns by card categories.

Customer Acquisition Cost: The Customer_Acq_Cost field reflects acquisition costs across card categories, similar to the acquisition cost visualizations in the dashboard.

Quarterly Data: The Qtr column tracks which quarter the transactions occurred, helping analyze quarterly trends (as seen in the dashboard's QTR Revenue and Transaction Count).

Expenditure Type: The Exp Type column can be mapped to the "Revenue by Expenditure Type" breakdown in the dashboard (e.g., Travel, Entertainment, Fuel).

Transaction Method: The Use Chip field records whether the customer used Chip, Swipe, or Online, which aligns with the "Revenue by Use Chip" dashboard analysis.
***

**Analysis from Dataset:**

Revenue Trends by Card Category: Use Card_Category and Total_Trans_Amt to visualize which card types generate the most revenue. The Blue card appears to have higher volumes.

Quarterly Performance: Track total transactions and revenue by quarter using Qtr, Total_Trans_Amt, and Total_Trans_Vol to identify peak performance periods, as shown in the Power BI dashboard.

Expenditure Type Insights: Using Exp Type and Total_Trans_Amt, identify the most popular spending categories like Bills, Entertainment, and Travel, similar to the dashboard breakdown.

Customer Acquisition Cost: With Customer_Acq_Cost, analyze which card categories or customer types incur the highest acquisition costs, potentially optimizing marketing efforts.

Utilization Ratio: The Avg_Utilization_Ratio could provide insights into how much of their credit customers are using, correlating it with revenue and risk of delinquency.
