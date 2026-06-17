# Bike Sales & Profitability Analysis

## Executive Summary

Purpose

This project analyzes bike sales performance using transactional sales data to identify key drivers of profitability across product categories, customer segments, products, and geographic markets. But despite strong overall sales performance, the business lacks clarity regarding which categories, customer segment, products and markets generate the greatest profitability and operational efficiency. Understanding these factors is necessary to support data-driven dscision making and resource allocation. This project analysis aims to address these problems and provide business recommendation to improve business profitability.

Findings & Conclusion

The findings reveal an upward trajectory in revenue and profit indicating strong business growth despite varying inconsistencies and inefficiencies. Accessories deliver the highest profit margin efficiency, while Bikes generate the largest share of overall profit despite operating at lower margins. Adults and Young Adults account for the majority of profit contribution with seniors performing the highest in profit margin efficiency. while no single product dominate in profit contribution some products cocnsistently show weaker margin performance. The findings also reveal United States and Austrialia as the business most valuable market both accounting for more than half of the business sales while Canada demonstrates the strongest margin performance among all markets despite relatively low revenue volume.

With these findings, the business now has a clear directive on which product categories, customer segments, products, and regions is the greatest profit contributors and which performed best in margin efficiency. This insight helps the business in better decision making and future investment.

Recommendation

The analysis also identified potential profitability inefficiencies across several products, categories, customer segments, and regions. Based on these findings, the following actions are recommended;

- Conduct a cost structure analysis across products, customer segments, and regions to identify profitability inefficiencies.
- Investigate production and operational processes to determine factors affecting margin performance.
- Evaluate pricing strategies across categories and markets to identify opportunities for improved profitability.
- Prioritize investment in high-margin categories and products to maximize profit growth.
- Explore growth opportunities in high-efficiency markets such as Canada.

This actions are recommended to improve overall profitability and support future business growth.

## Project Overview

This project analyzes bike sales performance across products, categories, customer segment and regions. The goal of this project is to identify profitability drivers, evaluate operational efficiency, uncover inefficienies and opportunities for business growth.

## Business Questions

1. Are we growing?
2. Which category is most efficient?
3. Which products drive profitability?
4. Which country is the most valuable market?
5. Which customer segment is the most profitable?

## Dataset Information

Source: Kaggle Bike Sales Dataset

Data Type: Retail Sales Transaction data

Original Dataset
- Records: 113,037
- Fields: 18

Post-Cleaning Dataset
- Records: 112,037
- Fields: 15

Tools Used
- Microsoft Excel.
- Pivot Table.
- pivot Chart.

## Methodology

This dataset was cleaned and analyze through the following steps and with the use of the following techniques.

Data Preparation
- Removal of duplicate records.
- Validation and recalculation of revenue and profit matrics.
- Standardization of gender values.
- Standardization of columns names for consistency.
- Removal of redundant date related field.

Analytical Techniques
- Data Cleaning.
- Data Validation.
- KPI Analysis.
- Dashboard Design.

## Key Performance Indicators (KPIs)

The business generated $94,688,588 in sales and also made a profit of $41,908,055 which amounted to a margin efficiency of 44,26%.

## Dashboard Overview

This dashboard provides an interactive view of sales performance, profitability, customer segments, products and country performance.

![Dashboard](Dashboard.png)


## Key Findings

# Finding 1 – Business Growth

Insight
The business demonstrates clear long term revenue and profit growth from 2011 to 2016, however this growth has not been consistent or efficient throughout the period. The most significant growth acceleration began in the middle of 2013, prior to which the business operated below its own long term average for nearly two and a half years. From January 2011 through mid 2013, profit margin consistently ranged between 38.51% and 41.03% — entirely below the business average of 44.26% — representing the weakest sustained efficiency period in the dataset. A notable turning point occurred from August 2013 onward where margins began recovering meaningfully, breaking above the business average and sustaining that improvement through 2014. However 2015 revealed a vulnerability — early months regressed sharply back below average before recovering in the second half of the year, suggesting the business has not yet achieved stable margin consistency across full calendar years. The highest margin performances recorded across the entire period were 55.59% in July 2014 and 55.53% in July 2016 — both isolated monthly peaks rather than sustained performance levels, indicating the business has demonstrated capacity for high efficiency but has not maintained it. A seasonal pattern is also evident — later months particularly from August through December consistently generate stronger revenue, profit and margin performance across multiple years, with December frequently recording the highest revenue of each year.

Hypothesis
The persistent below-average margin performance from 2011 through mid 2013 suggests high operational or manufacturing costs during the business's earlier growth phase that were not yet sufficiently controlled. The recovery from mid 2013 onward may reflect operational improvements, cost reductions or pricing adjustments introduced around that period. The recurring July margin spikes in 2014 and 2016 — both recording above 55% — may indicate a specific seasonal or promotional dynamic driving unusually high efficiency in that month, potentially lower costs or premium pricing during a peak demand period. The early 2015 regression back below average despite strong performance in 2014 suggests these efficiency gains were not yet structurally embedded into the business operations.

Recommendation
An investigation should be conducted into the 2011 to mid 2013 period to identify the specific cost or pricing factors that suppressed margin below the business average for an extended duration, ensuring those conditions are not recurring. The business should analyse what drove the July 2014 and July 2016 margin spikes to determine whether those conditions — whether pricing, product mix or cost factors — can be replicated or sustained beyond a single month. Strategic investment and sales activity should be concentrated in the second half of each year, particularly August through December, as this period consistently delivers the strongest revenue and profit performance across all years. Improving early year margin performance — particularly January through June — represents the clearest operational opportunity to raise the overall business average above 44.26%.

# Finding 2 – Category Efficiency

Insight
Accessories generated the highest profit margin among all categories, indicating the strongest profitability efficiency across the portfolio. Bikes produced the highest total profit in absolute terms but at a lower margin percentage, suggesting higher operational or production costs relative to revenue generated. Clothing recorded the weakest profit margin and the lowest profit contribution of all three categories, indicating poor profitability efficiency and limited impact on overall business performance.

Hypothesis
The lower margin efficiency in Bikes and Clothing may be driven by higher operational, manufacturing or supply chain costs relative to the revenue each category generates. Accessories' superior margin likely reflects lower production complexity or a more favourable cost to price ratio, allowing a greater proportion of revenue to convert to profit.

Recommendation
Strategic investment in Accessories should be increased given its strong margin efficiency and profitability potential — as every additional sale in this category converts to profit at a higher rate than any other. A cost structure analysis on Bikes and Clothing should be conducted to identify operational or production inefficiencies affecting profitability. Pricing strategy, supply chain operations and manufacturing processes for the lower performing categories should be reviewed with the goal of improving margin performance and closing the efficiency gap with Accessories.

# Finding 3 – Product Profitability

Insight
Among the top ten highest profit contributors, no single product stands out as a dominant driver — indicating the business is not heavily concentrated in a few products. However, four of the top ten products carry a consistently weak margin of 39.32%, suggesting low profitability efficiency despite their significant profit contribution. Two products stand out as efficiency leaders with margins of 62.86% — the highest among the top ten — demonstrating strong profitability relative to revenue generated. The remaining four products deliver relatively average margin performance, operating just above the business average of 44.26%.

Hypothesis
The weak margins of the Road-150 product variants are likely driven by high operational or production costs, or insufficient sales volume to achieve economies of scale. The consistency of 39.32% across all four Road-150 variants suggests a structural cost issue at the product line level rather than an isolated anomaly.

Recommendation
Strategic investment should be prioritised for the high margin products given their superior efficiency in converting revenue to profit. A cost structure analysis on the average performing products is required to identify any inefficiencies in operational or production costs. An urgent investigation into the Road-150 product line is recommended to determine whether high production costs or pricing gaps are responsible for the persistent margin underperformance.

# Finding 4 – Country Analysis

Insight
The United States and Australia stand out as the most valuable markets, together contributing approximately 59% of total business revenue. However, despite their high sales volume, both countries produce relatively average margin performance — indicating underlying profitability inefficiencies that limit how much of that revenue is converted to profit. The remaining four countries follow a similar pattern of average margin performance, with Canada being the notable exception at 47.35% — the highest margin of all six markets despite ranking last in revenue contribution.

Hypothesis
The below-average margin performance in the United States and Australia, as well as the other markets, may be driven by high operational or supply chain costs that are compressing profitability efficiency across all regions. Canada's superior margin despite low volume suggests the business model operates more efficiently there — possibly due to lower market costs or stronger pricing — making it a potentially underpenetrated market.

Recommendation
A cost structure analysis should be conducted across all countries to identify inefficiencies in production, operational or supply chain costs. Strategic investment should be considered for each market given their collective growth potential. The United States and Australia warrant deeper focus as the business's most valuable markets by revenue and profit contribution. Canada in particular merits a dedicated growth strategy — its leading margin efficiency proves the business model works there and incremental investment could yield disproportionate profit returns.

# Finding 5 - Customer Segment Profitability

Insight
Adults have proven to be the business's most profitable customer segment, generating approximately half of total business profit. Young Adults follow as the second largest contributor at just above 35% of total profit. Youth and Seniors generate the least profit in absolute terms, with Seniors contributing less than 1% of total business profit. However, despite this negligible volume, Seniors deliver the highest profit margin of all segments at nearly 50% — the only segment approaching that threshold.

Hypothesis
All four segments, despite their varying profit contributions, produce relatively average margin performance — with the exception of Seniors. This pattern across Adults, Young Adults and Youth may be driven by high operational costs that are suppressing margin potential across the broader customer base.

Recommendation
A cost structure analysis across all segments should be conducted to identify operational inefficiencies and improve margin performance. The business should concentrate investment on Adults and Young Adults as they have proven to be the most profitable customer groups at scale. A strategic investment case should also be made for the Seniors segment — despite their very low profit contribution in absolute terms, their near-50% margin is the highest of any segment, indicating strong profitability efficiency and a potential opportunity for significant growth if sales volume can be increased.

## Limitations
With the findings and recommendations completed, there are few things i noticed within the data when analyzing. There was operational and manufacturing cost breakdown as well as supply chain, as a results recommendations were dased on obserevd sales and profitablity patterns only.


## Conclusion
The analysis identified revenue and profit growth across business years, accessories has the most efficient category, adults as the most profitable customer segment with United States and Australia as the business most valuable market.
The analysis also revealed potential profitability inefficiencies across several product lines and regions suggesting opportunities for operational optimization and strategic investment.
