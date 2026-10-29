# ShopNest E-Commerce Sales & Operations Analysis | Power BI

## Project Overview

ShopNest is an e-commerce analytics project focused on understanding sales performance, revenue trends, customer payment preferences, product ratings, and order fulfilment.

This project uses **Power BI** to transform raw e-commerce data into interactive dashboards that support business analysis and data-driven decision-making.

## Business Objectives

- Analyse revenue and sales performance across years and states.
- Identify the top-performing product categories.
- Monitor on-time and delayed order fulfilment.
- Evaluate monthly delivery trends and identify categories with higher delays.
- Understand customer payment method preferences.
- Identify the top 10 highest-rated and bottom 10 lowest-rated products.
- Present key performance indicators through an executive dashboard.

## Tools & Technologies

- **Power BI:** Interactive dashboards, data modelling, visualisation and reporting.
- **Power Query:** Data preparation, transformation and integration.
- **DAX:** Measures, KPIs, product-rating analysis and business calculations.
- **Data modelling:** Relationships between customers, orders, products, order items, payments, reviews and supporting tables.

## Dashboard Pages

### 1. Executive Overview

Provides a consolidated view of ShopNest's overall sales and operational performance.

![ShopNest Executive Overview](<Shopnest - Exicutive Overview.png>)

**Key metrics displayed:**
- Total Revenue: 16.01M
- Total Sales: 13.59M
- Total Orders: 99,441
- Average Order Value: 159.33
- On-Time Orders: 88,649
- Delayed Orders: 7,827
- Average Product Rating: 4.09

**Key analyses:**
- State-wise sales performance
- Annual revenue trends
- Top 10 product categories by sales
- Interactive filtering by year and customer state

### 2. Delivery Details & Order Fulfilment

Focuses on order-level delivery information and fulfilment performance.

![ShopNest Delivery Details](<Shopnest - Delivery Details.png>)

**Key analyses:**
- Order-level delivery status
- Actual versus expected delivery dates
- Total, on-time and delayed order counts
- Identification of delayed orders for further investigation

### 3. Performance Analysis

Examines operational performance, delivery patterns, customer payment preferences and product ratings.

![ShopNest Performance Analysis](<Shopnest - Performace Analysis.png>)

**Key analyses:**
- Delayed orders by product category
- Monthly comparison of delayed and on-time orders
- Top 10 highest-rated products
- Bottom 10 lowest-rated products
- Distribution of payment methods

## Key Business Insights

- **Revenue growth:** Annual revenue increased from approximately 7.2M in 2017 to 8.7M in 2018.
- **Order fulfilment:** The dashboard records 88,649 on-time orders and 7,827 delayed orders, highlighting the importance of monitoring delivery performance.
- **Category-level delays:** Bed, bath and table; health and beauty; and sports and leisure appear among the categories with the highest delayed-order counts.
- **Product categories:** Health and beauty and watches and gifts are among the leading categories by sales.
- **Payment preferences:** Credit cards account for the largest share of recorded payment value.
- **Product ratings:** Separate top 10 and bottom 10 analyses help identify highly rated products and products that may need further investigation.

*Insights reflect the figures and rankings displayed in the dashboard and may change when filters are applied.*

## Technical Approach

### Data Preparation & Modelling
- Prepared and integrated the relevant e-commerce datasets.
- Established relationships between the tables to support cross-functional analysis.
- Created a date table to enable year-wise and month-wise analysis.
- Configured data fields and measures for consistent reporting.

### DAX & Business Calculations

- **Total Revenue:** Calculated as the sum of `payment_value` from the `Order_Payments` table, representing the total recorded payment value.
- **Total Sales:** Calculated as the sum of `price` from the `Order_Items` table, representing the total product sales value excluding freight charges.
- Developed measures for total orders, average order value and average product rating.
- Used actual and expected delivery dates to analyse on-time and delayed orders.
- Implemented ranking logic to identify the top 10 highest-rated and bottom 10 lowest-rated products.
- Analysed payment values by payment method to understand payment distribution.

### Dashboard Design
- Designed three complementary pages for executive reporting, delivery details and performance analysis.
- Added interactive slicers and visual-level filtering.
- Used KPI cards, bar charts, column charts, a map visual, a donut chart and a detailed order table.

## Skills Demonstrated

Power BI | DAX | Power Query | Data Modelling | Data Cleaning | KPI Development | Business Intelligence | Data Visualisation | E-Commerce Analytics | Operational Analysis

## Conclusion

The ShopNest project demonstrates how Power BI can be used to analyse e-commerce sales, revenue, product performance, customer payment preferences and delivery operations. The interactive dashboards bring key business metrics together and help identify trends and areas requiring further investigation.

---

**Project Type:** Data Analytics Capstone Project  
**Domain:** E-Commerce | Sales & Operations Analytics  
**Primary Tool:** Microsoft Power BI
