Supermarket Sales Analysis

Project Overview :
This project explores supermarket sales data to extract meaningful insights using data wrangling, exploratory data analysis (EDA), and visualization techniques. The dataset contains transaction details from multiple branches, including sales amounts, customer ratings, payment methods, and more.

 Objectives:
1.Identify trends and correlations in sales performance.
 2.Analyze customer purchasing behavior.
 3.Provide data-driven business recommendations to optimize decision-making.
 Dataset Information:
 1. Source: Supermarket Sales Dataset
 2.Size: Contains multiple rows and columns capturing transaction details
 Key Features: 
 1. Branch: Store locations (Yangon, Naypyitaw, Mandalay)
 2.Quantity: Number of items purchased per transaction
 3. Tax 5%: Sales tax applied on purchases
 4.Total: Final transaction amount after tax
 5.Rating: Customer satisfaction score (1-10 scale)
 6.Date & Time: Purchase timestamp for trend analysis

Data Wrangling & Preprocessing :

1.Handled Missing Values → Checked for null values and ensured data consistency.
 2.Removed Duplicates → Maintained data integrity by eliminating redundant records.
 3.Standardized Data Formats → Converted date columns to datetime format and normalized numerical values.
 4.Feature Engineering → Extracted additional insights by deriving month, day, and time-based attributes for better analysis.
  
Data Analysis & Insights :

1️.Feature Correlation Heatmap :
Key Observations:
1.Strong positive correlation between Total and Tax 5% (0.98), confirming tax is directly proportional to sales.
2. Moderate correlation between Quantity and Total (0.7), indicating that larger purchases lead to higher revenue.
3.No significant correlation between Customer Rating and Sales Performance, suggesting that customer satisfaction does not directly impact total sales.
2.Branch Performance Analysis :
 Key Findings:
1.Different sales patterns were observed across the three supermarket branches.
2.Naypyitaw showed a negative correlation (-0.49) with Mandalay, suggesting a difference in customer preferences or market conditions.
3.Time-Based Trends :
Key Insights:
1.Monthly and daily sales trends reveal fluctuations in purchase behavior, which could be leveraged for seasonal promotions.
2.Sales show higher activity during weekends, suggesting peak shopping days for targeted marketing campaigns.
3. Afternoon and evening transactions dominate the dataset, indicating optimal sales hours for staffing and inventory planning.

Business Recommendations :


1.Optimize Inventory Management → Adjust stock levels based on high-demand trends in different branches.
2. Time-Based Promotions → Offer targeted discounts during slow sales periods to boost revenue.
3. Enhance Marketing Strategies → Focus on weekend promotions and branch-specific campaigns.
4. Monitor Customer Experience → Improve engagement strategies since customer ratings do not significantly affect sales.

Tools & Technologies Used :

 Python (Pandas, NumPy, Matplotlib, Seaborn) → Data wrangling & visualization
 Jupyter Notebook → Analysis and reporting
 GitHub → Version control & collaboration
