# Tech-Tech-Campaign-Report


# Project Background
Backround about the company, including the industry, active years, business model, and key business metrics. Explain this from the POV of a data analyst who is working at the company.
Fresh Cart is an e-commerce company that has been actively leveraging various digital platforms to drive online sales. It operates within the online retail industry, where optimizing ad spend and conversion rates is crucial for maintaining profitability and growth. Fresh Cart's business model revolves around targeting diverse audiences across platforms which includes YouTube, Twitter, Facebook, Instagram, and Google Ads. The focus of this analysis is to understand the performance of these platforms from a data analytics perspective and provide actionable insights to optimize future campaigns.


Insights and recommendations are provided on the following key areas:

- **Category 1:Platform Effectiveness** 
- **Category 2:Cost per Conversion**
- **Category 3:Return on Ad Spend (ROAS)**
- **Category 4:Campaign Frequency and Duration** 

The SQL queries used to inspect and clean the data for this analysis can be found here [link].

Targed SQL queries regarding various business questions can be found here [link].

An interactive Tableau dashboard used to report and explore sales trends can be found here [link].



# Data Structure & Initial Checks

Fresh Cart's main database structure consists of four tables, each capturing specific data relevant to its ad campaigns. Here's a breakdown of the tables and their contents:

- **Table 2:Platform Performance**
- **Table 3:Conversion Data**
- **Table 4:Ad Spend Breakdown**
- **Table 5:Campaign Analytics**

[Entity Relationship Diagram here]



# Executive Summary

### Overview of Findings

The analysis of Fresh Cart's advertising platforms reveals that YouTube is the most effective platform, with the highest Return on Ad Spend (ROAS), lowest cost per conversion, and maximum sales revenue. On the other hand, Google Ads is the least efficient, showing the highest cost per conversion and lowest ROAS. These insights suggest that reallocating advertising budgets to more effective platforms like YouTube could significantly improve Fresh Cart’s digital advertising efficiency.


[Visualization, including a graph of overall trends or snapshot of a dashboard]



# Insights Deep Dive
### Platform Effectiveness:

* **Main insight 1.** YouTube and Twitter shows high conversion rates (6.41% and 6.79% respectively), surpassing the industry average of 1.4% Youtube and 0.77%Twitter.
  
* **Main insight 2.**  YouTube is more cost-effective with a $2.72 cost per conversion compared to Twitter's $14.21. This indicates that YouTube provides better value for Fresh Cart’s ad spend.
  
* **Main insight 3.** YouTube's ROAS is significantly higher at 1298.84%, meaning Fresh Cart earns $12.99 for every dollar spent. In contrast, Twitter's ROAS is 420.18%, which indicates room for improvement in optimizing spend on this platform.
  
* **Main insight 4.** Despite running fewer campaigns, YouTube generates more sales revenue of ($29K) while Twitter sales revenue was ($28K), with about 1k difference highlighting its overall efficiency.

[Visualization specific to category 1]


### Cost per Conversion:

* **Main insight 1.** YouTube emerges as the most cost-effective platform with a cost per conversion of $2.72.
  
* **Main insight 2.** Twitter's cost per conversion is significantly higher at $14.21, suggesting that it requires optimization in terms of ad targeting and spend allocation.
  
* **Main insight 3.** Google Ads shows the highest cost per conversion at $35.00, making it the most expensive platform for acquiring customers.
  
* **Main insight 4.** Facebook and Instagram have moderate costs per conversion ($16.68 and $26.16, respectively), indicating that they are mid-range options in terms of cost-efficiency.

[Visualization specific to category 2]


### Return on Ad Spend (ROAS):

* **Main insight 1.** YouTube has the highest ROAS (1298.84%), offering the most substantial return on investment for Fresh Cart.
  
* **Main insight 2.** Twitter’s ROAS, while positive, is much lower at 420.18%, indicating that Fresh Cart is spending more on Twitter campaigns to achieve similar sales results to YouTube.
  
* **Main insight 3.** Facebook's ROAS is lower than YouTube and Twitter, at 229.75%, highlighting potential areas for improvement in targeting and campaign execution.
  
* **Main insight 4.** Google Ads performs the worst in terms of ROAS (170.88%), signaling the need for a reassessment of the strategy for this platform.

[Visualization specific to category 3]


### Campaign Frequency and Duration:

* **Main insight 1.** YouTube achieved higher returns despite running fewer campaigns of (9) than Twitter which was (12), suggesting that campaign quality and content are more important than quantity.
  
* **Main insight 2.** Campaign duration also played a role, with YouTube having shorter ad durations (average 3.11 days) yet driving more significant results compared to the platform Twitter (4.33 days). YouTube still outperformed, indicating a better alignment with audience preferences and more impactful content.
  
* **Main insight 3.** Facebook and Instagram have relatively shorter ad durations, but this doesn’t seem to negatively impact their overall conversion rates.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 4]



# Recommendations:

Based on the insights above, the following recommendations are proposed that the [stakeholder team] to consider the following: 

* Increase investment in YouTube campaigns. YouTube consistently delivers high conversion rates, lower costs per conversion, and excellent ROAS. Additional budget allocation to this platform will likely yield better returns for Fresh Cart.**
  
* Optimize Twitter ad spend. Although Twitter has strong conversion rates, its high cost per conversion suggests inefficiencies. Consider refining targeting, ad creatives, and frequency capping to maximize ROAS.**
  
* Reassess Google Ads strategy. With the highest cost per conversion and lowest ROAS, Google Ads is underperforming. The need to explore alternative keywords and ad formats, and consider reducing spend in favor of higher-performing platforms.**
  
* Explore more campaigns on YouTube. Given YouTube's success despite running fewer campaigns, Fresh Cart should consider increasing the number of YouTube ads or extending the duration of successful campaigns.**
  
  

# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 Missing data for specific campaigns was estimated based on historical trends.
  
* Assumption 1 Refunds and returns were not accounted for in the conversion value calculations due to data limitations.
  
* Assumption 1 Campaign effectiveness was primarily measured based on ROAS, but factors like customer lifetime value were not included.

