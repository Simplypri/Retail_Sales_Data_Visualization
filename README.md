Results and Insights

Retail Sales Data Visualization – Superstore Dataset

This section summarizes the analytical findings derived from descriptive, visual, and interactive analytics applied to the U.S. Superstore retail dataset. The results are organized by analytical objectives, highlighting key insights, business implications, and improvement plans supported by data visualizations.

Objective 1: Descriptive & Visual Analysis of Retail Performance
Exploratory Data Analysis (EDA)

Initial exploration involved reviewing dataset structure, summary statistics, and data quality checks. No major missing values or type inconsistencies were identified. Histograms of numerical variables revealed strong right skewness in Sales and Profit, while categorical distributions highlighted dominant segments, shipping modes, and product categories.

Key Findings

Correlation Analysis:
A correlation heatmap revealed a strong positive relationship between Sales and Profit, while other numerical variables showed weaker or negligible correlations.

Customer Concentration:
A bar chart of the top 10 customers by total sales showed that a small group contributes disproportionately to revenue.

Temporal Trends:

Monthly sales trends showed clear seasonality and fluctuations.

Boxplots of sales by weekday revealed performance differences across days.

Pareto Effect:
Pareto analysis confirmed the 80/20 rule, where a small percentage of customers generate the majority of sales.

Regional & Product Insights:

Some regions generate high sales but relatively lower profits.

Certain product categories and sub-categories show high revenue but poor profitability, indicating margin inefficiencies.

Business Implication

This EDA provided a comprehensive foundation for deeper analysis by identifying top-performing customers, regions, and products, as well as areas with low or negative profitability that require strategic attention.

Objective 2: Identifying High- and Under-Performing Products
Methodology

Product-level performance was analyzed in Power BI by aggregating total sales and profit per product. Using quartile-based classification, products were grouped into:

High-Performing

Under-Performing

Low-Margin

Moderate

A scatterplot (Sales vs. Profit) with color-coded performance categories enabled intuitive exploration.

Key Findings

High-Performing Products:
Items such as Canon imageCLASS 2200 Advanced Copier and Fellowes PB500 Electric Punch Binding Machine delivered strong sales and profits, primarily within Technology and Office Equipment categories.

Under-Performing Products:
Low-sales, loss-making items (e.g., Bookcases, Desk Accessories) emerged as candidates for discontinuation or restructuring.

Low-Margin Products:
Products with high sales but weak or negative margins indicated over-discounting or high fulfillment costs.

Sunburst Analysis

A sunburst chart revealed hierarchical profit patterns:

Technology sub-categories (Phones, Accessories) dominate profitability.

Furniture items (Tables, Bookcases) frequently show losses.

Strategic Implications

Prioritize marketing and logistics support for high-performing SKUs.

Reevaluate pricing, bundling, or discontinuation strategies for under-performers.

Review cost structures for low-margin, high-volume products.

Objective 3: Impact of Discounts on Profitability
Analysis Approach

Using Observable HQ, data was aggregated by sub-category to compute average discount, profit margin, and total sales. Interactive bubble charts and violin plots were used to analyze discount–profit relationships.

Key Findings

Furniture:
Furnishings show strong margins with low discounts, while Bookcases and Tables suffer losses due to heavy discounting.

Office Supplies:
Labels, Envelopes, and Paper exhibit high margins and low discounts; Binders and Appliances show high sales but negative margins.

Technology:
Copiers are high-margin with moderate discounts; Machines incur losses due to aggressive discounting.

Visualization Insights

Bubble charts effectively highlighted trade-offs between discount levels, sales volume, and profitability.

Violin plots showed that higher discounts correlate strongly with negative profits, especially in Technology and Office Supplies.

Strategic Implications

Cap discounts on loss-making items.

Bundle high-margin, low-volume products.

Implement margin alerts and regularly monitor discount effectiveness.

Objective 4: Operational Efficiency via Shipping Timeline Analysis
Methodology

Shipping delays were calculated as the difference between Ship Date and Order Date. Aggregated averages were visualized using heatmaps and contour plots.

Key Findings

The Central region exhibited the highest average delays, particularly for Office Supplies.

Other regions showed relatively consistent performance around 3.9–4.0 days.

Contour plots revealed temporal spikes and seasonal logistics disruptions, especially in Central and West regions.

Business Implications

Target logistics audits in high-delay regions.

Improve supplier coordination and fulfillment automation.

Use dashboards for continuous operational monitoring.

Objective 5: Customer Segmentation & Purchasing Behavior
Segment–Category Relationships

A chord diagram illustrated sales flows between customer segments and product categories:

Consumer segment contributes the highest overall sales, particularly in Technology.

Corporate follows closely, while Home Office contributes the least.

Technology receives the largest sales share across all segments.

Temporal Trends

Stacked bar charts highlighted quarterly sales patterns, with consistent Q4 peaks.

Stacked area charts showed long-term growth and shifting segment contributions over time.

Strategic Implications

Focus Consumer-targeted promotions on high-performing categories.

Tailor Corporate and Home Office strategies for under-represented categories.

Align inventory and campaigns with seasonal peaks.

Objective 6: Geographic Sales Pattern Analysis
Geographic Insights

Choropleth maps revealed strong concentration in California, New York, and Texas.

Several states showed minimal sales, indicating under-penetrated markets.

Treemaps reinforced regional disparities and highlighted sales concentration.

Strategic Opportunities

Expand distribution and marketing in low-sales states.

Conduct localized market research.

Empower regional sales teams with targeted incentives and analytics.

Overall Conclusion

This multi-objective analysis integrates descriptive statistics, advanced visualizations, and interactive dashboards to deliver actionable insights across products, customers, regions, pricing, and operations. The findings support data-driven decision-making in pricing, inventory management, marketing strategy, and supply-chain optimization—laying a strong foundation for scalable retail analytics and business intelligence.