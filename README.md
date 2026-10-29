# Market Expansion and Product Strategy

Use Power BI to analyze business performance, identify international market opportunities, and develop data-driven product strategies.

## I. Introduction

### 1. Dataset Description

#### Orders Table

| Column Name | Data Type | Description |
|---|---|---|
| Category | STRING | Product category |
| City | STRING | Customer city |
| Country | STRING | Customer country |
| Customer ID | STRING | Unique customer identifier |
| Customer Name | STRING | Customer name |
| Market | STRING | Sales market |
| Order Date | DATE | Date the order was placed |
| Order ID | STRING | Unique order identifier |
| Postal Code | INTEGER | Customer postal code |
| Product ID | STRING | Unique product identifier |
| Product Name | STRING | Product name |
| Profit | FLOAT | Profit generated from the order |
| Quantity | INTEGER | Quantity of products ordered |
| Region | STRING | Sales region |
| Sales | FLOAT | Total sales amount |
| Segment | STRING | Customer segment |
| Ship Date | DATE | Date the order was shipped |
| Ship Mode | STRING | Shipping method |
| State | STRING | Customer state or province |
| Sub-Category | STRING | Product sub-category |

#### People Table

| Column Name | Data Type | Description |
|---|---|---|
| Person | STRING | Regional manager or sales representative |
| Region | STRING | Assigned sales region |

#### Returns Table

| Column Name | Data Type | Description |
|---|---|---|
| Order ID | STRING | Unique order identifier |
| Returned | STRING | Order return status |

### 2. Business Problem

- Present international market performance to senior management.
- Highlight key business metrics to support decisions about which markets to expand into and which products to prioritize in each international market.
- Identify opportunities to increase revenue while maintaining profitability and controlling operational risks.

## II. Design Thinking

### Step 1: Empathize

<img width="1277" height="537" alt="Empathize - Image 1" src="https://github.com/user-attachments/assets/28b3a22a-9290-4c91-8529-0e2c7e7ff34e" />

**Insight**

Senior management needs a clear overview of international business performance to identify growth opportunities, understand profitability, and allocate resources effectively.

<img width="1176" height="641" alt="Empathize - Image 2" src="https://github.com/user-attachments/assets/a526f7c9-8126-43d2-99b0-4060979fc7e4" />

**Insight**

Market expansion decisions require more than revenue figures. Profit margins, customer distribution, product performance, and return rates should also be considered to avoid prioritizing markets that generate sales but deliver limited profit.

### Step 2: Define POV (Point of View)

<img width="1121" height="628" alt="Define POV - Image 1" src="https://github.com/user-attachments/assets/88e7d85a-8126-43d2-99b0-4060979fc7e4" />

**Insight**

The key business challenge is to identify markets with attractive growth potential and products that can generate sustainable profits, while accounting for differences in market performance and customer demand.

<img width="1033" height="506" alt="Define POV - Image 2" src="https://github.com/user-attachments/assets/2ca99ce5-7506-4b82-9c9f-91f7b3269a56" />

**Insight**

Decision-makers need to compare markets and product categories using consistent KPIs. Revenue growth, profit margin, customer base, and return rate provide complementary perspectives for evaluating expansion opportunities.

### Step 3: Ideate

<img width="1416" height="630" alt="Ideate" src="https://github.com/user-attachments/assets/9ec6309c-5dc0-4f22-ba90-b82e6f50fcee" />

**Insight**

A three-part analytical approach—market analysis, product analysis, and customer analysis—can help connect market opportunities with product profitability and customer demand.

### Step 4: Prototype and Review

- Select appropriate charts and visualizations for each business question.
- Design the report layout, including KPI cards, chart placement, and page navigation.
- Apply a consistent color palette and visual hierarchy.
- Review the dashboard for accuracy, readability, and business relevance.
- Refine the report to make insights and decision-making opportunities easier to identify.

## III. Visualization

### 1. Business Overview

<img width="1153" height="647" alt="Business Overview Dashboard" src="https://github.com/user-attachments/assets/33547721-26b7-4e86-b225-3f10dbc812f4" />

**Insight**

Revenue increased by 51.5%, from $8.34M to $12.64M, while profit increased by 52.3%, from $963K to $1.47M. However, the customer base grew only slightly, from 1,575 to 1,590 customers.

This suggests that revenue growth was driven primarily by higher sales per existing customer or changes in sales mix, rather than substantial customer acquisition. The limited customer growth also highlights the importance of evaluating customer concentration and retention.

### 2. Market Analysis

<img width="1167" height="648" alt="Market Analysis Dashboard" src="https://github.com/user-attachments/assets/ddfeeebb-7527-4ccc-93af-3a420d309bab" />

**Insight**

Market performance varies considerably across regions. The EU generates approximately $3M in revenue, while Canada reports a relatively high profit margin of 26.62% despite having only 201 orders. Africa generates approximately $784K in revenue with a reported profit margin of 11.34%.

These differences suggest that markets should be evaluated based on both scale and profitability. Smaller markets with stronger margins may offer opportunities for expansion, while markets with weaker profitability require further investigation before additional investment.

### 3. Product Analysis

<img width="1162" height="655" alt="Product Analysis Dashboard - Image 1" src="https://github.com/user-attachments/assets/7ed40459-43c8-4581-b3f8-7edcec3587b3" />

**Insight**

Copiers have the highest reported profit and profit margin among the analyzed sub-categories, suggesting an opportunity to prioritize this product category in markets where demand and distribution capabilities support expansion.

In contrast, Phones generate substantial revenue but have relatively low margins, indicating that sales volume alone may not reflect product profitability.

<img width="1167" height="652" alt="Product Analysis Dashboard - Image 2" src="https://github.com/user-attachments/assets/021f7fd7-b7b8-4cf4-8ed7-a61162171657" />

**Insight**

Tables have maintained negative profit margins over four years, indicating a persistent profitability issue. Continuing to expand sales without addressing the underlying causes could increase losses.

Pricing, discount levels, shipping costs, and product-level profitability should be reviewed before deciding whether to reposition or discontinue the sub-category.

### 4. Customer Analysis

<img width="1157" height="652" alt="Customer Analysis Dashboard" src="https://github.com/user-attachments/assets/8fe9682c-5bdf-46fe-b44f-8255681ad2d9" />

**Insight**

Revenue has grown substantially while the total customer count has remained relatively stable. This may indicate increased spending among existing customers or a greater contribution from a small number of high-value customers.

Customer-level revenue and profit analysis can help determine whether growth is broadly distributed or concentrated among a few accounts, supporting decisions about retention, acquisition, and customer portfolio diversification.

## IV. Insights and Recommendations

| Insight | Recommendation |
|---|---|
| Revenue increased by 51.5%, from $8.34M to $12.64M, while profit increased by 52.3%, from $963K to $1.47M. The customer base grew only slightly, from 1,575 to 1,590. Although the business is growing, customer acquisition has not kept pace with revenue growth. | Evaluate sales performance using both revenue and profit, rather than revenue alone. Consider assigning 60% of sales performance evaluation to profit and 40% to revenue. Introduce a proposed minimum profit margin threshold of 8% for orders, subject to validation against the company's actual cost structure and market conditions. Require regional manager approval for deals below the threshold. |
| Revenue grew substantially while the customer base increased by only 15 customers. This may indicate that revenue growth depends heavily on existing customers or a small number of high-value accounts. | Analyze revenue and profit contribution by customer to identify concentration risk. Expand customer acquisition alongside retention initiatives, and reduce dependence on a small number of key accounts by diversifying the customer portfolio. |
| Africa generates approximately $784K in revenue with a reported profit margin of 11.34% and a return rate of 0%. This suggests potential for further growth, although the return-rate result should be validated. | Investigate demand, customer growth, logistics costs, and product profitability in Africa before increasing investment. Pilot expansion in promising product categories and monitor revenue, profit margin, and return rate to validate the opportunity. |
| Canada reports a profit margin of 26.62% across 201 orders, suggesting attractive profitability despite a relatively limited order volume. | Test targeted marketing and sales initiatives to increase customer acquisition and order volume in Canada. Track incremental revenue, profit, customer acquisition cost, and margin to confirm that expansion remains profitable. |
| Copiers have the highest reported profit and profit margin among product sub-categories, suggesting potential for expansion in suitable markets. | Evaluate demand, competitive conditions, and product-level profitability for Copiers in the EU and Canada. Run a controlled expansion or inventory pilot before increasing stock allocation, and monitor sales growth, inventory turnover, and profit margin. |
| Phones generate high revenue but have relatively low profit margins, suggesting that sales volume may be supported by discounts or other costs that reduce profitability. | Review discount levels, pricing, and fulfillment costs for Phones. Test more targeted discounts and compare revenue, conversion rate, and profit per order to identify pricing strategies that improve profitability without unnecessarily reducing sales. |
| APAC generates more than $1.3M in revenue from Technology and Furniture, with reported return rates of approximately 6–7%. The market shows meaningful sales volume, but returns may reduce realized profitability. | Maintain investment in the stronger product categories while investigating return reasons by product and country. Address recurring quality, delivery, or product-description issues and monitor return rate and profit margin after improvements. |
| The EU generates approximately $3M in revenue, with profit margins of around 10–13% and reported growth of approximately 55%. Return rates of 6–6.8% may create opportunities to improve operational performance. | Continue developing Technology and Office Supplies while reviewing discounting practices and return drivers. Prioritize profitable growth and monitor incremental profit, return rate, and margin before expanding promotional spending. |
| The US demonstrates strong profitability but may have additional revenue growth opportunities. The available summary does not establish which product categories or customer segments have the greatest untapped potential. | Segment US performance by product category, customer segment, and sales channel to identify profitable growth opportunities. Test expansion of complementary products and targeted marketing campaigns, measuring incremental revenue and profit rather than sales volume alone. |
| LATAM revenue is increasing, but profit margins remain relatively low. This indicates that sales growth may not be translating into proportional profit growth. | Review discounting, shipping costs, product mix, and average order value in LATAM. Prioritize products and customer segments with stronger margins, and expand investment selectively based on incremental profit and margin improvement. |
| Africa and EMEA are reported to have relatively high customer counts but negative profit in some segments or reporting periods. This suggests that customer volume alone may not be sufficient to ensure profitability. | Investigate profit and loss by country, product category, discount level, shipping cost, and return status. Develop corrective actions for loss-making segments and consider reducing or exiting them only after confirming that the losses are persistent and that improvement opportunities are limited. |
| Tables have maintained negative profit margins over four years, indicating a persistent profitability issue rather than a short-term fluctuation. | Review Tables pricing, discount levels, shipping costs, and product-level margins. Test price adjustments or reduced discounting where commercially feasible. If the category remains unprofitable after corrective actions, consider reducing its assortment or discontinuing selected products. |
| Revenue growth has outpaced customer growth, but aggregate figures alone do not reveal whether revenue is concentrated among a few customers. | Build a customer contribution analysis using revenue and profit share by customer. Monitor the percentage of revenue generated by the top 5 or top 10 customers, and combine retention strategies for valuable accounts with acquisition efforts to diversify revenue sources. |

---

## V. Conclusion

The analysis highlights several potential opportunities for international market expansion and product optimization. Canada appears attractive based on its reported profit margin, while Copiers may offer product-level growth opportunities in selected markets. Meanwhile, Phones and Tables require closer profitability reviews, and markets with negative profit need further investigation before additional investment.

The recommended strategy is to prioritize **profitable growth over revenue growth alone**. By combining market-level performance, product profitability, customer contribution, and return-rate analysis, management can allocate resources more effectively and make expansion decisions based on measurable business outcomes.
