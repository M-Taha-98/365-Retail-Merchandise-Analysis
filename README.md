# 365-Retail-Merchandise-Analysis

## 🔗 **Project Background**
365 Retail, established in 2023 as a premium lifestyle brand for a prominent social media influencer, features a diverse portfolio spanning apparel, gifting, and bespoke customized goods. This comprehensive performance audit seeks to synthesize sales data, consumer behavior patterns, and emerging business trends to identify critical drivers of commercial success and refine the brand’s global market positioning.

Insights and recommendations are provided on the following key areas:

-	**Sales Trends Analysis:** Evaluation of historical sales patterns, focusing on high-level Key Performing Indicators (KPIs): Revenue, Average Order Value (AOV) and Average Customer Rating.
-	**Product Level Performance:**  An analysis of product verticals, their performance over time and identification of best sellers and those lacking.
-	**Market Performance:** An evaluation of metrics: Sales, Units Sold, AOV across regions, comparison of local vs international regional business performance, and categorizing that across gender split.
-	**Customer Ratings & Feedback:** An assessment of the customer feedback across different markets and products, impact on revenue and transactions, and identification of common bottlenecks in performance driving poor ratings and reviews.
  
An interactive Power BI dashboard used to report and explore trends can be found [here.](https://app.powerbi.com/view?r=eyJrIjoiMzZjMWQ5NGItYzliYS00OTQ3LWI4YWYtNTFhOTJjOTIyYmU1IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


## 📆 Data Structure

The merchandise’s database structure as seen below consists of four tables: transactions, customers, market_lookup, and dim_calendar, with a total of 7,500 records. 

<p align="center">
  <img src="https://github.com/M-Taha-98/365-Retail-Merchandise-Analysis/blob/main/Assets/Data%20model.png" width="400" />
</p>


## 📝 Executive Summary

The brand has maintained a trajectory of steady growth, with monthly revenues scaling from $62,000 to a peak of approximately $73,000. While the domestic market remains robust, recent volatility has emerged within international segments, most notably in the UK. High-growth opportunities have been identified in India and Canada, where demand for the core "Clothing" vertical remains strong but is currently offset by localized performance gaps. This report outlines strategic interventions to stabilize international revenue shares, optimize product-category alignment, and address fulfillment-related sentiment risks.


<p align="center">
  <img src="https://github.com/M-Taha-98/365-Retail-Merchandise-Analysis/blob/main/Assets/dashboard_snap.png" width="700" />
</p>


## 📊 Insights Deep Dive
### Sales Trends:

<p >
  <img src="https://github.com/M-Taha-98/365-Retail-Merchandise-Analysis/blob/main/Assets/v6_revenue_trend.png" align="right" width="600" />

* Over the inaugural year (November 2023 – November 2024), 365 Retail generated over **$850,000 in gross revenue**, supported by a healthy Average Order Value (AOV) of $116 and a baseline customer rating of 3.5/5.
* **Monthly revenue has seen steady growth over the year**, reaching a high-water mark of $80,000 in May 2024, with order volumes consistently ranging between 550 and 650 units, peaking at 668 orders in January 2024.
* Localized fluctuations require attention: the **US domestic market experienced revenue contractions** of 20% and 12% below the domestic monthly average in June and August 2024, respectively, while **international revenue saw a significant 20% downturn** in September 2024, falling to $25,500.
</p>

<br clear="right"/>

### Product Performance:

<p align="center">
  <img src="https://github.com/M-Taha-98/365-Retail-Merchandise-Analysis/blob/main/Assets/v4_product%20quality.png" width="600" />
</p>

* **"T-Shirt" serves as the brand’s primary volume driver**, accounting for 20% of total unit sales ($190k+ revenue), whereas "Wall Flags" represent a niche segment at 2% of total volume. 
* A critical **performance gap exists within the premium catalog** (Premium Hoodies and Zip Jackets), which suffers from consistently low ratings across several markets—reaching a nadir of 3.11 and 3.07 respectively in Canada. These metrics suggest latent quality control issues and/or shipping disruptions that are currently throttling the growth of high-margin SKUs.
* Demographically, Gen-Z and Millennial cohorts show identical basket values (~$116). Male consumers drive 70% of revenue ($600k), over twice that as females, with a **shared preference for the Clothing vertical**, which commands three-quarter of total revenue share.


### Market Analysis:

<p align="center">
  <img src="https://github.com/M-Taha-98/365-Retail-Merchandise-Analysis/blob/main/Assets/v1_UK%20trend.png" height = "399" width = "479" />
  <img src="https://github.com/M-Taha-98/365-Retail-Merchandise-Analysis/blob/main/Assets/v2_UK%20trend.png" height = "400" width = "501"/>
</p>

* The **US remains the anchor market**, contributing 55% ($470k) of total revenue. **Internationally, the UK ($157k) and India ($74k) lead**, while the rest of markets cumulatively contribute around 15%.
* The **UK market signaled an urgent risk in October 2024: order volume hit an all-time low of 60 units**, yielding $8,000 in revenue, 40% below its monthly average of $13,364 up until September 2024. This decline coincided with a drop in customer satisfaction (from 60% to 51.7%) and a record-low rating of 3.13 in the clothing vertical, **indicating immediate friction in regional fulfillment or quality assurance**.
  
<p>
  <img src="https://github.com/M-Taha-98/365-Retail-Merchandise-Analysis/raw/main/Assets/v3_Canada%20trend.png" align="right" width="450" />

* **In Canada** which contributes nearly 6% of the revenue share, highest after the major markets of US, UK and India, **the brand faces an Average Order Value (AOV) deficit**. While Canadian consumers demonstrate strong purchasing power with the highest Units Per Transaction (UPT) at 1.73, the Average Unit Retail (AUR) remains disproportionately low at $77.46, lowest amongst all international markets. Analysis confirms this is not a lack of interest in clothing vertical negating product mix shift towards lower price-tier, but a **missed opportunity in seasonal alignment**; only 35% of sales are high-value winter-wear (zip jacket and hoodie), despite Canada’s winter-accumulated climate, suggesting a need for more aggressive promotion of premium winter outerwear.
</p>

<br clear="right"/>

### Customer Feedback:

* Data confirms a **direct correlation between high ratings and conversion velocity**. The **"Other" product vertical remains the most significant drag on brand sentiment** with consistently lowest ratings in the international market apart from Canada, due to suspected transit damage and handling issues in international lanes. The quality issues can be further verified through return claims with availability of return transactions data.

<p align="center">
  <img src="https://github.com/M-Taha-98/365-Retail-Merchandise-Analysis/blob/main/Assets/v5_India%20trend.png" width="650" />
</p>

* **Sentiment risks are particularly acute in India**, where the "Ornaments" and "Other" categories have seen satisfaction levels plummet, with 35% and 31.5% of customers reporting negative experiences, respectively. This is amongst the highest ratio of dissatisfied customers for these two product verticals. This dissatisfaction in a high-growth market underscores the necessity of investigating the material perception of goods upon delivery and the integrity of international shipping protocols.


## 📈 Recommendations:

Based on the insights and findings above, the stakeholder(s) are recommended to consider the following: 

**1. Strategic Inventory & Catalog Refinement:**
- **Canadian Seasonal Market Penetration:** The notorious Canadian winter provides a clear missed opportunity for grabbing a larger share of the Canadian winter-wear market. Pivot **marketing spend toward "Winter-Wear"** essentials in Canada to capitalize on geographic demand. Scaling the volume of premium zip jackets and hoodies will increase the Average Unit Retail (AUR) and drive overall AOV growth.

- **Inventory Lifecycle Optimization:** Execute a strategic **phase-out of the "Disk Figurine"** based on its sustained low-rating status and minimal sales volume. Reallocate resources from underperforming assets toward higher-velocity categories to improve portfolio health.
  
**2. Operational & Fulfillment Optimization:**
- **Expectation-Delivery Parity in High-Value Indian Market:** The high Avg Unit Retail ($122.8) and lower unit per transaction (1.67) points to **perceived value mismatch** upon delivery. Leverage the high AUR in the Indian market by implementing rigorous quality control and **"anti-damage" shipping protocols**. Aligning in-person product perception with the premium price point is vital to improving customer sentiment and transaction depth.
- **Premium Catalog Bottlenecks (Quality-to-Conversion Alignment):** Initiate a diagnostic audit of the Premium Hoodie and Zip Jacket lines to **identify fulfillment or manufacturing friction**. Resolve localized shipping disruptions in Canada to unlock dormant demand for high-tier products.
- **UK Market Performance:** Address the critical dip in UK clothing ratings (3.13) by **auditing the supply chain for quality inconsistencies**. Stabilizing the "clothing vertical" is essential to protecting the revenue share of this secondary global market.

**3. Marketing & Customer Acquisition (CAC) Efficiency:**
- **Rating-Driven Ad Bidding:** Since high ratings correlate with conversion, integrate a **Dynamic Product Feed** into social ads that only promotes products with a 4.0+ rating. Using the "Zip Jacket" as an example: if its rating in Canada is 3.07, it should be excluded from "Top-of-Funnel" ads in that region until the quality/shipping bottleneck is resolved.
- **Gender-Based Vertical Scaling:** With males driving 70% of revenue ($600k), current ROAS is likely much higher on male-targeted ad sets. **70/30 Budget Split** is recommended favoring male-centric lifestyle content for the Clothing vertical.
- **Sentiment-Driven Conversion Scaling:** **Dynamically feature high-rated products** in "Top Rated" or "Customer Favorites" sections on the homepage and in email marketing to increase the conversion rate of existing traffic. **Reallocate ad spend** toward products that already have a "high-rating" status for better ROAS.


## 🔎 Further Analysis:

Data of return transactions and delivery lead time can help in the following analysis:

**1. Logistics Impact on Sentiment:**
- **Shipping Lead Time vs. Rating Correlation:** Conduct a comparative analysis between "Days to Deliver" and "Average Rating" to **quantify the impact of transit delays on customer sentiment**. Use these insights to isolate logistics-driven dissatisfaction for certain product verticals, particularly within high-stakes markets like India.
  
**2. Category-Specific Friction:**
- **Return Rate Vertical Segmentation:** Audit return rates across specific product categories in low-satisfaction markets to identify disproportionate outliers. Pinpoint root causes—such as transit damage or "expectation vs. reality" gaps—to implement corrective measures like **enhanced packaging, alternate shipping partner consideration, optimized text and visual product messaging on websites, or pre-purchase customer support**, especially for international customers.


## Let's Connect:

<p align="center">
  <a href="https://www.linkedin.com/in/mohammadtaha-businessanalytics/">
    <img src="https://img.shields.io/badge/View%20Profile%20on-LinkedIn-0077B5?logo=linkedin&logoColor=white" alt="LinkedIn Profile"/>
  </a>
  <a href="https://www.upwork.com/freelancers/~01158dbad6fc20cf59">
    <img src="https://img.shields.io/badge/View%20Profile%20on-Upwork-6fda44?logo=upwork&logoColor=white" alt="Upwork Profile"/>
  </a>
    <a href="https://www.fiverr.com/taha_mohammad?public_mode=true">
    <img src="https://img.shields.io/badge/View%20Profile%20on-Fiverr-1DBF73?logo=fiverr&logoColor=white" alt="Fiverr Profile"/>
  </a>
</p>
