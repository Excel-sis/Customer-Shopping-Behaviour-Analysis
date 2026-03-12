# Customer-Shopping-Behaviour-Analysis
This project analyses customer shopping behaviour to uncover insights into sales performance, product effectiveness, and customer engagement patterns. The analysis identifies revenue concentration risks, subscription underperformance, gender imbalance in spending, and opportunities for product diversification and customer retention optimization.

## Business Objectives

The analysis was aimed at achieving the following business objectives;

**Analyze Customer Purchasing Behavior**

To understand how customers shop by examining purchase frequency, spending patterns, and buying trends.

**Evaluate Product Performance**

To identify the best-performing product categories and top-selling items that contribute most to overall revenue.

**Measure Business Performance**

To track key metrics such as total revenue, average revenue per transaction, total customers, and average customer spending.

**Understand Customer Demographics**

To analyze customer segments based on age group, gender, and location in order to identify the most valuable customer groups.

**Identify Sales Trends and Patterns**

To explore seasonal sales trends and understand how different periods of the year influence purchasing behavior.

**Examine Payment Preferences**

To determine the most commonly used payment methods among customers.

**Support Data-Driven Decision Making**

To provide clear insights that help businesses improve marketing strategies, product planning, and inventory management.

**Improve Product and Inventory Strategy**

To identify popular product attributes such as size and item type so businesses can optimize stock levels and meet customer demand.

    
## Dataset Used


## Dataset Overview
The dataset contains information about customer demographics, purchasing patterns, product preferences, and engagement behavior. The dataset is designed to help analyze how different factors such as age, gender, product category, discounts, and subscription status influence customer spending and loyalty.

The dataset includes 3,900 customer records with multiple attributes describing customer transactions and behaviors. Each record represents a purchase made by a customer and includes details about the product purchased, the amount spent, payment method, purchase frequency, and customer review ratings.

The data provides valuable insights into customer segmentation, revenue drivers, shopping habits, and engagement levels, making it suitable for building a business intelligence dashboard that supports data-driven decision making.

**Key areas of analysis supported by this dataset include:**

      •	Customer demographics and segmentation
      •	Sales and revenue performance
      •	Product category performance
      •	Customer engagement and loyalty
      •	Discount and promotion impact
      •	Payment method preferences
      •	Customer satisfaction through review ratings
      
Overall, this dataset enables analysts to explore patterns in consumer behavior, identify opportunities for improving customer retention, and support strategic decisions in marketing, sales, and product management.

## Data Preparation

      •	Data loading
      •	Imported raw data into Power Bi Desktop
      •	Confirmed data structure and inspected column types 

## Data Cleaning & Transformation (Power Query)

      •	Checked for blank rows and columns (none identified)
      •	Created DAX measures and KPIs

## Data Modelling

Created calculated columns and DAX measures for;

      •	Total Revenue
      •	Total Customers
      •	Revenue %
      •	Average Review Rating
      •	Average Purchase Value
      •	Average Previous Purchases
      •	No of Unique Items
      •	Repeat Customer %
      •	Age Column

## Visualization

      •	Designed a clean, Business-Standard and user- friendly dashboard
      •	Included slicers for frequency of purchase, season, gender and location to enable dynamic analysis
      •	Added KPI cards for quick review
      •	Used column charts, bar charts, pie charts, donut chart and text boxes

## Formatting & Branding

      •	A consistent theme for visual clarity was applied.
      •	Used layout alignment, colors and icons to enhance readability.

## Sales Performance Analysis





**Key KPIs Used;**

        •	Total Revenue: $233,081
        •	Average Revenue per Transaction: $59.76
        •	Total Customers: 3,900
        •	Average Previous Purchases: 25.35

**Visualizations**
        
        -    Revenue by Category
        -    Revenue by Frequency of Purchase
        -    Top 5 Selling Items by Revenue
          
## Key Insights

**Revenue by Category**

The result gotten from the analysis shows that clothing generates approximately 45% of total revenue,  making it the core revenue driver and thereby creating category dependency risk.

**Business Risk:** Overreliance on a single category increases vulnerability to demand shifts.

**Recommendation:** Diversify revenue streams through product bundling and category expansion.

**Revenue by Frequency of Purchase**

This proved that revenue distribution across purchase frequency types is relatively balanced, with quarterly and bi-weekly customers contributing slightly more.

**Insight:** Moderate-frequency buyers are major revenue stabilizers.

**Recommendation:** Develop targeted retention campaigns for these segments.

**Top 5 Selling Items by Revenue**

•	These showed that the top-selling items which were the blouse, shirt, dress, pants and jewelry generated similar revenue levels.

**Insight:** Top performing items are primarily clothing products, reinforcing the category dominance.

**Recommendations:**
    
        1.	Promote bundles (blouse + jewelry)
        2.	Ensure constant stock availability of top 5 items.
        3.	Use these items for marketing campaigns.

## Product Performance Analysis 

**Key KPIs**

        . Total Revenue
        . Best Category
        . Average Reviews Rating
        . Number of Unique Items

**Visualizations**

        -    Revenue by Season and Category
        -    Sales by Payment Method
        -    Purchase by Size
           
**Seasonal Analysis – Revenue by Season and Category**

Seasonal breakdown observations:

        -    Spring experienced the highest clothing sales
        -    Winter had Strong seasonal demand
        -    Sales during Fall was Stable
        -    Summer sales had a slight dip

**Insights:**

        1.	Clothing performs well year round.
        2.	Seasonal impact exists but is not extreme
        3.	Outerwear increases slightly in winter/ fall as expected

**Recommendation:**

        1.	Push seasonal promotions (e.g Outerwear in winter).
        2.	Offer summer fashion bundles to boost summer revenue

**Sales by Payment Method**

The result gotten indicated that payment usage was evenly distributed and this means that customers are comfortable with multiple payment options and no strong dependency on a single payment channel.

**Size Distribution – Purchase by Size**

        •	Size “M” significantly outperforms other sizes.

**Recommendations:**

        •	Maintain higher inventory levels for size M
        •	Avoid overstocking XL and S.
        •	Use sales/discounts to clear slower sizes.

**Customer Behavior Analysis** 

**Key KPIs**

        •	Total Customers
        •	Average Spend per Customer
        •	Total Orders
        •	Repeat Customers

**Visualisations**

        -    Sales by Age Group
        -    Sales by Gender
        -    Sales by Discount
        -    Sales by Subscription
        -    Sales by Location
        
**Sales by Age Group**

        1.	25-34 and 45-54 age group generate the highest sales.
        2.	Customers aged 18-24 contribute the least revenue among active buyers.
        3.	Middle-aged customers (25-54) dominate spending.
        4.	Customers in the working class age range have the highest purchasing power.

**Recommendation:**

        1.	Target 25-54 age group with premium offers and loyalty programs.
        2.	Use student discounts or youth campaigns to grow the 18-24 segment.

**Sales by Gender**

Male customers (67.74%) contribute over two-thirds of total revenue. The business appeared to attract more male buyers or higher male spending.

**Recommendation:**

        1.	Introduce marketing campaigns targeting female customers.
        2.	Expand female-oriented product offerings.

**Sales by Discount**

More sales occured without discounts ($134k) and discounts still drove a significant portion of sales.

**Insights:** Customers are willing to purchase even without price reductions, suggesting: 
        
        1.	Strong product value.
        2.	Brand or product loyalty.
        
**Recommendation:**

        1.	Use discounts strategically during slow sales period.
        2.	Avoid over-discounting to maintain profit margins.

**Sales by Subscription**

This shows that more revenue comes from non-subscribed customers (73%).
The subscription program may be underutilized.

**Recommendation:**
        
        1.	Introduce exclusive benefits for subscribers.
        2.	Offer early product access, discount rewards, free-shipping.
        
These could help increase loyalty and predictable profit.
    
**Sales by Location**

This revealed that that the sales distribution across states is relatively balanced and no single state dominates overall revenue.
The company has a diverse geographic customer base.

**Recommendation:**

        1.	Identify high-potential states for regional marketing campaigns.
        2.	Expand advertising in top-performing locations.
            
##Strategic Recommendations##

        •	Improve subscription value proposition and benefits.
        •	Target underrepresented customer segments.
        •	Enhance product quality control processes.
        •	Optimize inventory management based on size demand.
        •	Diversify product portfolio to reduce dependency risk.
        •	Focus on improving customer engagement through loyalty programs, personalized marketing, post-purchase incentives, and enhanced customer experience to improve customer retention and increase long-term customer lifetime value.

##Tools Used##

        o	Excel, Power Query and Power BI

##Conclusion##

    -    The business demonstrates stable revenue performance and diversified item-level sales; however, strategic improvements are required in subscription engagement, category diversification, and demographic expansion.
    -    By implementing targeted retention strategies and product optimization initiatives, the company can significantly improve customer lifetime value and revenue sustainability.

##Dashboard##
