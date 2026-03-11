# customer-shopping-behavior-analysis

## Table Of Contents
[Project Overview](#project-overview)

[Business Objectives](#business-objectives)

[Dataset Overview](#dataset-overview)

[Data Preparation](#data-preparation)

[🧾 Sales Performance Analysis (Page 1)](#-sales-performance-analysis-page-1)

[📦 Product Performance Analysis (Page 2)](#-product-performance-analysis-page-2)

[👥 CUSTOMERS PERFORMANCE (Page 3)](#-customers-performance-page-3)

[Strategic Recommendations](#strategic-recommendations)

[Conclusion](#conclusion)

## Project Overview
This project analyzes customer shopping behavior to uncover insights into sales performance, product effectiveness, and customer engagement patterns.

Using Microsoft Power BI, the dashboard explores purchasing trends across 3,900 transactions, focusing on how product categories, customer demographics, and subscription behavior influence overall revenue.

The analysis highlights several important patterns including revenue concentration risks, subscription underperformance, gender imbalance in spending, and opportunities to improve customer retention and product diversification.

### Business Objectives

The analysis aims to answer key business questions:
1. What factors drive total revenue?
2. Which product categories and items perform best?
3. How do customer demographics influence purchasing behavior?
5. How effective is the subscription model?
6. Where are the main growth opportunities?

### Dataset Overview

The dataset contains 3,900 transaction records with 16 attributes, including:

###### Customer Demographics
- Age
- Gender
- Location

###### Purchase Information
- Product Category
- Item Purchased
- Size
- Season

###### Financial Metrics
- Purchase Amount

###### Engagement Indicators
- Subscription Status
- Previous Purchases
- Review Rating

### Data Preparation

#### Data Loading

The raw dataset was imported into Power BI Desktop, and column structures were verified to ensure correct data types.

#### Data Cleaning (Power Query)
- Checked for missing values and blank rows (none detected)
- Verified data consistency across fields
- Prepared data for modeling and visualization

 #### Data Modeling

Several calculated measures and KPIs were created using DAX to support deeper analysis:
- Total Revenue
- Total Customers
- Revenue Percentage
- Average Review Rating
- Average Purchase Value
- Average Previous Purchases
- Number of Unique Items
- Repeat Customer Percentage
- Age Group Column

These metrics formed the backbone of the analytical dashboard.

###  Dashboard Design

The Power BI dashboard was designed to provide clear, interactive business insights.

Features included
- KPI cards for high-level performance tracking
- Interactive slicers for:
- Gender
- Season
- Location
- Purchase Frequency
- Visualizations including:
- Column charts
- Bar charts
- Pie charts
- Donut charts
- Text insight boxes

### Project Insights

#### 🧾 Sales Performance Analysis (Page 1)
![image](https://github.com/user-attachments/assets/31fcb813-814b-4e29-84e5-747d33826f98)

##### Key KPIs
- Total Revenue: $233,081
- Average Revenue per Transaction: $59.76
- Total Customers: 3,900
- Average Previous Purchases: 25.35

###### Revenue by Purchase Frequency
1. Highest Revenue comes from every three months ($ 35.1k)
2. Closely followed by annually ($ 34.4k) and quarterly ($33.8k).
3. Weekly purchases generate the least ($31.8k) but the gap is small.

Insights: 
-Customers who purchase less frequently actually generate slightly more revenue than frequent weekly buyers.

Recommendations: 
-Introduce loyalty and subscription incentives to increase purchase frequency without reducing basket value.
 
###### Revenue by Category
1. Clothing: $104k (highest)
2. Accessories: $74k
3. Footwear: $36k
4. Outerwear:$19k (lowest)
   
Insights: 
- Clothing contribute nearly 45% of total revenue, making it the core revenue driver.
  
Recommendations:
- Expand clothing inventory and promotions.
- Bundle low performing categories (outerwear) with clothing.
- Cross sell accessories with clothing items.

###### Top 5 Revenue Generating Items
1. Blouse -$10.4k
2. Shirt -$10.3k
3. Dress -$10.3k
4. Pants -$10.1k
5. Jewelry -$10.0k
   
Insights: 
- Top performing items are primarily clothing products, reinforcing the category dominance.
  
Recommendations:
- Promote bundles (blouse + jewelry)
- Ensure constant stock availability of top 5 items.
- Use these items for marketing campaigns.
 


### 📦 Product Performance Analysis (Page 2)
![image](https://github.com/user-attachments/assets/c214a8e6-3fb5-487a-a37a-a123c5f4683d)


##### Key KPIs
- Average Review Rating: 3.75 / 5
- Unique Items: 25
- Best Performing Category: Clothing ($ 104.26k) 

###### Revenue by Season
Seasonal breakdown observations:
- Spring ($28k clothing) - Highest clothing sales
- Winter ($27k clothing) - Strong seasonal demand
- Fall ($26k clothing) – Stable
- Summer ($23k clothing) – Slight dip

Insights:
- Clothing performs well year round.
- Seasonal impact exists but is not extreme
- Outerwear increases slightly in winter/ fall as expected
  
Recommendation:
- Push seasonal promotions (e.g Outerwear in winter).
- Offer summer fashion bundles to boost summer revenue.

###### Category Performance Insights
- Clothing dominates by generating 45% of total revenue, performs strongly across all seasons and clearly the core revenue driver.
- Accessories is the second best performer with stable contribution across seasons ads good cross selling potential with clothing.
- Footwear and Outerwear are moderate but have consistent performance.
- Outerwear is the lowest contributor.

Recommendation:
- The company is highly dependent on clothing sales. Diversifying growth into Accessories and Footwear could reduce category risk.

###### Sales by Payment Method
1. Credit Card - $40k
2. Paypal - $40k
3. Cash - $39k
4. Debit Card - $39k
5. Venmo - $37k
6. Bank Transfer - $37k
   
Insights: 
- Payment usage is evenly distributed.
This means Customers are comfortable with multiple payment options and no strong dependency on a single payment channel.

Recommendation:
- Offer small incentives for digital payments to reduce cash handling.
- Partner with digital payment providers for cashback campaigns.

###### Purchases by size 
Medium size dominates significantly with 44k.

Recommendations:
- Maintain higher inventory levels for size M
- Avoid overstocking XL and S.
- Use sales/discounts to clear slower sizes.
  
###### Top Purchase Counts
1. Jewelry (Gray, M) - 262 purchases
2. Coat ( Violet , M)- 228
3. Skirt (Black , L)- 224
4. Handbag (Charcoal , M) -224
5. Pants (Charcoal , M) -218
   
Observations:
- Medium size appears repeatedly.
- Neutral colours (Gray, Black, Charcoal) performs best.
- Accessories like Jewelry and handbags are high volume items.
  
Recommendation:
- Stock more neutral coloured products.
- Promote bundles (Handbag + Jewelry).
- Focus marketing on best-selling colours.

### 👥 CUSTOMERS PERFORMANCE (Page 3)
![image](https://github.com/user-attachments/assets/2ba653eb-790a-42b1-91af-20ba9670cded)

- Total Customers: 3.9k
- Total Orders: 4k
- Average Spend per Customer : $60
- Repeat Customer Rate: 1.00
This shows a strong customer retention level, where most customers return to make additional purchases.

###### Sales by Age
1. 25-34 and 45-54 age group generate the highest sales.
2. Customers aged 18-24 contribute the least revenue among active buyers.
3. Middle-aged customers (25-54) dominate spending.
4. Customers in the working class age range have the highest purchasing power.
   
Recommendation:
- Target 25-54 age group with premium offers and loyalty programs.
- Use student discounts or youth campaigns to grow the 18-24 segment.
  
###### Sales by Gender
Male customers (67.74%) contribute over two-thirds of total revenue. The business appears to attract more male buyers or higher male spending.

Recommendation:
- Introduce marketing campaigns targeting female customers.
- Expand female-oriented product offerings.
  
###### Sales by Discount
More sales occur without discounts ($134k) and discounts still drive a significant portion of sales.

Insights:

Customers are willing to purchase even without price reductions, suggesting:
- Strong product value.
- Brand or product loyalty.
  
Recommendation:
- Use discounts strategically during slow sales period.
- Avoid over-discounting to maintain profit margins.

###### Sales by Subscription
More revenue comes from non-subscribed customers (73%).
The subscription program may be underutilized.

Recommendation:
- Introduce exclusive benefits for subscribers.
- Offer early product access, discount rewards, free-shipping.
By doing these could help increase loyalty and predictable profit.

###### Sales by Location
Sales distribution across states is relatively balanced and no single state dominates overall revenue.
Montana - $5.8k, Illinois - $5.6K, California - $5.6k, Idaho - $5.6k, Nevada - $5.5k
The company has a diverse geographic customer base.

Recommendation:
- Identify high-potential states for regional marketing campaigns.
- Expand advertising in top-performing locations.

### STRATEGIC RECOMMENDATIONS
1. Introduce personalized promotions based on purchase frequency.
2. Increase marketing focus on clothing (core revenue driver).
3. Improve customer experience to raise review ratings.
4. Optimize inventory around size M and neutral colors.
5. Increase Female customer engagement.
6. Expand subscription program.

### CONCLUSIONS
The analysis shows that the business generated $233k in revenue from 3.9k customers with clothing emerging as the top-performing category. Products such as Blouses, Shirts and Dresses drive the highest sales. Customer purchases are consistent across different buying frequencies, with medium-sized items being the most demanded. Sales are also evenly distributed across payment methods and seasons, indicating stable customer behavior. A dominant middle-age purchasing segment, strong repeat customer behavior, high male spending contribution. Overall, the insights highlight opportunities to improve customer satisfaction, target younger demographics, optimize inventory and grow lower-performing product categories.
