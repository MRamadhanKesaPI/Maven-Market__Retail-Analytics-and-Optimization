# Maven Market: Retail Business Analytics and Optimization Report

## Table of Contents
- [**Project Background**](#project-background)
- [**Project Assets**](#project-assets)
- [**Data Structure and Initial Checks**](#data-structure-and-initial-checks)
- [**Insights**](#insights)
- [**Recommendations**](#recommendations)

## Project Background
Maven Market, a fictional retail brand, started in the mid-1990s and offers a wide variety of consumer products. By 1997, it had expanded across North America (United States, Canada, and Mexico) and collected valuable sales, product, and customer data. However, this data wasn’t fully used for strategic decisions.

This project analyzes two years of data (1997–1998) to uncover insights that improve profitability, product offerings, customer satisfaction, and efficiency. The focus is on topline performance, product evaluation, customer trends, and operational metrics to guide business growth.

### Insights and Recommendations Focus:
The project highlights four key areas of improvement:

1. [Executive Summary](#executive-summary),
reviews overall performance, including revenue, order trends, and profit margins.

2. [Product Performance](#product-performance),
examines profit margins, sales targets, and product returns.

3. [Customer Behavior](#customer-behavior),
analyzes customer retention and acquisition trends over two years.

4. [Operational Efficiency](#operational-efficiency),
evaluates store performance and revenue per square foot across regions.


## Project Assets
To make the analysis and insights easy to explore, the following resources are available:

- The SQL queries for data preparation can be found [here](https://mramadhankesapi.github.io/Data-Preparation-Process__for__Maven-Market...Retail-Analytics-and-Optimization/)

- The DAX measures for data analysis and analysis questions can be found [here](https://mramadhankesapi.github.io/DAX-Measures__for__Maven-Market...Retail-Analytics-and-Optimization/)

- The Power BI dashboard can be downloaded here: [Maven Market Dashboard.pdf](https://github.com/user-attachments/files/18228058/Maven.Market.Dashboard.pdf)

**Note**: Due to issues with my Microsoft account, the  interactive Power BI content will be updated once technical issues with my Microsoft account are resolved.


## Data Structure and initial Checks
The Maven Market database contains seven tables: customers, products, stores, regions, calendar, returns, and orders, with a total of 289,511 rows.

![full_name](https://github.com/user-attachments/assets/5918f224-027c-44de-8bc9-a2f46f588e7a)

Before beginning the analysis, comprehensive quality checks were performed to ensure data preparation and to familiarize with Maven Market's datasets. The SQL queries for data preparation can be found [here](https://mramadhankesapi.github.io/Data-Preparation-Process__for__Maven-Market...Retail-Analytics-and-Optimization/)


## Insights
### Executive Summary
Maven Market achieved strong financial results in 1998, with a $1.05M profit and a 59% profit margin, driven by expansion into Mexico and Canada. Revenue grew by 112% compared to the previous year, supported by strong product performance.

The USA remains the top revenue source, but Mexico’s rapid growth in just one year shows it could soon compete the USA. This highlights Mexico’s strong market potential and growing customer demand.

"Hermano" is the top-selling brand, contributing 3.21% of total sales, while "Plato" leads with the highest profit margin of 63.6%, showcasing operational efficiency despite lower revenue. These results set the stage for further analysis and growth opportunities.

A detailed overview of these insights is available in the Power BI dashboard, which can be downloaded here:  [Maven Market Dashboard.pdf](https://github.com/user-attachments/files/18228058/Maven.Market.Dashboard.pdf)

![EXE SUMMARY](https://github.com/user-attachments/assets/bd0dd2bb-cf1f-4b63-a099-699ba282fc71)


### Product Performance:
- "Best Choice" generates $42,738 in revenue with a 60.6% profit margin, showing consistent upward sales trends and strong performance.
- "Plato" and "BBB Best" have the highest profit margins (63.6% and 62.1%, respectively) but lower sales (~$30K). Adjusting prices slightly could boost sales while maintaining profitability.
  
**Note**: The report includes a drillthrough page in Power BI for detailed product insights. Selecting a product brand in any of the pages will updates this dashboard with specific brand selected.

![Product Detail 1](https://github.com/user-attachments/assets/07b44c5a-df9d-4794-b7ea-2e0b6f401ac1)

![Product Detail 2](https://github.com/user-attachments/assets/23782158-3def-4122-83f5-e00cc1dc2c29)


### Customer Behavior:
- Maven Market had 8,842 customers over two years, with 8,060 joining in 1998, indicating rapid growth that year.
- A 98.8% retention rate shows strong customer loyalty and satisfaction.
- Bronze membership generates the most revenue, particularly from lower and middle-income customers, offering an affordable option, better than having no membership at all (the "normal" status).

![Customer Behaviors](https://github.com/user-attachments/assets/430427b2-70be-4470-a048-4243dd164ed0)


### Operational Efficiency:
- USA stores achieve high revenue per SQFT ($3.24) with a low order frequency (28), indicating fewer but higher-value purchases. In contrast, Mexico has a higher order frequency (66) but lower revenue per SQFT ($1.74), suggesting frequent but smaller transactions. The opportunity lies in boosting order frequency in the USA and Canada while increasing order values in Mexico to balance both performance metrics.
- We focus on USA stores as they have been running for two years. Stores like Store 14, Store 2, and Store 22 consistently underperform, earning under $0.50 revenue per square foot, highlighting the need for further evaluation.

![Operational Efficiency](https://github.com/user-attachments/assets/467e5d00-ead8-4167-be73-1aa82c7cbe2f)


## Recommendations
1. Adjust Pricing for High-Margin, Low-Sales Products:
   - **Recommendation**: Slightly adjust prices for products like Plato and BBB Best to boost sales while maintaining strong profit margins. If this successful, apply to other similar products.
   - **Rationale**: These products have high profit margins but low sales. Small price adjustments or targeted promotions could drive more volume without compromising profitability.

2. Bundle or Reposition Low-Performing Products Outside Top 50:
   - **Recommendation**: Bundle or reposition products outside the top 50, especially those generating under $10k in revenue, to reduce inventory costs and boost sales.
   - **Rationale**: Products with low revenue can benefit from bundling or repositioning to improve sales and inventory turnover. Successful strategies with these low-revenue products can be scaled to other underperforming items.

3. Leverage Mexico's Growth Potential:
   - **Recommendation**: Increase marketing and distribution efforts in Mexico to capitalize on its rapid growth and close the gap with the USA in revenue.
   - **Rationale**: Despite being operational for only one year, Mexico's rapid growth indicates untapped potential. Expanding marketing efforts and optimizing product offerings can accelerate its revenue growth.
  
4. Optimize Underperforming USA Stores:
   - **Recommendation**: Investigate underperforming stores (e.g., Store 14, Store 2, Store 22) for operational issues and consider reallocation of resources or store closures.
   unlike stores in other countries, which have only been open for one year,
   - **Rationale**: These stores have been operating for two years, unlike stores in other countries, which have only been open for one year. Despite the longer operating time, these stores still underperform. Addressing operational issues or reallocating resources could improve their performance and profitability.

5. Maximize Customer Retention and Upsell Membership Tiers:
   - **Recommendation**: Enhance the Bronze membership program with additional benefits and create a pathway for customers to upgrade to higher tiers.
   - **Rationale**: With a 98.8% retention rate, focusing on increasing revenue from loyal customers through tiered memberships will maximize lifetime value.




