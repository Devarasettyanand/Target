Target SQL

Target Corporation is an American retail corporation that operates a chain of discount department stores and hypermarkets, headquartered in Minneapolis, Minnesota. It is the seventh-largest retailer in the United States.Target is notable for its focus on upscale, trend-forward merchandise at lower costs.Its stores typically sell general merchandise—including clothing, household goods, electronics, toys, and more—as well as groceries.Its main competitors include Walmart and Amazon.


PROBLEM STATEMENT

This business case focuses on the operations of Target in Brazil and provides insightful information about 100,000 orders placed between 2016 and 2018. The dataset offers a comprehensive view of various dimensions including the order status, price, payment and freight performance, customer location, product attributes, and customer reviews.


GOAL

Analyzing the given dataset to extract valuable insights:
Evaluate Operational Efficiency
Understand Customer Behavior 
Optimize Product Performance
Enhance Customer Satisfaction
Drive Data-Driven Decision Making

ER-Diagram

<img width="503" height="304" alt="image" src="https://github.com/user-attachments/assets/e27b7c32-247e-4023-8c58-50c32cee3e6e" />


Dataset: https://drive.google.com/drive/folders/1TGEc66YKbD443nslRi1bWgVd238gJCnb

The data is available in 8 csv files:

1. customers.csv
2. sellers.csv
3. order_items.csv
4. geolocation.csv
5. payments.csv
6. reviews.csv
7. orders.csv
8. products.csv


OBSERVATIONS

State vs Total Orders :

Top 5 States (SP, MG, RJ, RS, PR) contribute to the bulk of the orders, with SP (38,108 orders) accounting for over 50% of the total volume.

Bottom 5 States (RO, AM, AC, AP, RR) reflect low consumer activity, with RR contributing the least (36 orders).

State vs Freight Charges :

States with lower order volumes (such as RR, AP, and AC) are likely to incur higher freight costs per order due to distance and less frequent deliveries.

High-order states (SP, MG)  benefit from economies of scale and reduced average shipping costs.

State vs Customer Base :

SP is the largest customer base, implying higher urban density and purchasing power.

States like RR and AP have limited customer penetration, suggesting room for growth through customer acquisition campaigns.

Payment Insights :

Payment Method Preferences -

UPI leads both order volume and payment value, particularly in high-order states.

Credit Cards are the second most popular method, especially for high-ticket items.

Debit Cards and Vouchers account for a small fraction of total transactions.

Payment Installments -

Single payments dominate (over 50% of orders).

Installments between 3-10 months are popular, while 12+ month plans have minimal adoption.

Seasonal Trends -

January, November, and December are the busiest months for both UPI and Credit Card payments.

September reflects moderate activity, suggesting potential for a pre-holiday push.


RECOMMENDATIONS

1. High-Performing States (SP, MG, RJ, RS, PR)
Exclusive Loyalty Programs: Implement tier-based reward programs to encourage frequent purchases.
Personalized Promotions: Offer state-specific deals aligned with their preferred payment methods.
Priority Delivery: Introduce same-day or next-day delivery for these regions to maintain a competitive edge.

2. Low-Performing States (RO, AM, AC, AP, RR)
Localized Campaigns: Design hyper-local advertising in regional languages to engage underrepresented areas.
Strategic Partnerships: Partner with local delivery services to reduce freight costs and improve delivery speed.
Community Outreach: Use community influencers to build trust and promote the brand in smaller markets.

3. Reduce Delivery Time in Key Regions
Set up localized warehouses in regions with high order volumes (SP, MG).
Implement AI-based delivery routing to shorten transit times.
Smart Inventory Allocation.

4. UPI & Credit Card Optimization
Exclusive Discounts: Offer UPI-exclusive cashback or credit card EMI discounts to drive usage.
Promote Contactless Payments: Push UPI-first marketing during festive seasons and flash sales.

5. Increase Adoption of Debit Cards and Vouchers
Limited-Time Offers: Provide exclusive product access or extra discounts for voucher users.
Introduce zero-cost EMIs for debit card transactions to boost large-order adoption.

6. Customer Acquisition & Retention
Increase Customer Base in Low-Performing States.
Drive Customer Loyalty in High-Performing Regions.


CONCLUSION

In conclusion, Target's data-driven insights reveal clear opportunities to enhance operational efficiency and customer satisfaction. By focusing on high-performing states, optimizing logistics in low-demand regions, and leveraging popular payment methods, Target can drive sustainable growth. Strengthening seasonal marketing strategies and tailoring payment options will further boost customer engagement and sales. With a strategic, data-backed approach, Target is well-positioned to maximize market share and deliver exceptional value to its customers.
