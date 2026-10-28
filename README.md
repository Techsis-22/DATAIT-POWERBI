# FMCG Sales Performance, Collection Risk and Product Analysis

## 1. Project Overview

This project presents an interactive Power BI dashboard developed to analyse sales performance, collection efficiency, outstanding receivables, product performance, and outlet contributions within an FMCG business environment.

The dashboard transforms sales and collection data into business insights that can help management evaluate revenue performance, monitor profitability, identify collection risks, and understand the products and sales channels contributing to business results.

The project focuses on three major areas:

1. **Sales Performance Overview:** Evaluates sales revenue, gross sales, profit margin, sales volume, average unit price, and sales distribution across channels and time.
2. **Collection Risk Analysis:** Examines confirmed collections, outstanding amounts, order counts, collection rates, and outstanding balances across outlets and channels.
3. **Product and Outlet Performance:** Analyses product categories, subcategories, outlet tiers, manufacturers, sales targets, and sales contributions.

The dashboard was designed to support data-driven decision-making by presenting business performance indicators in an interactive and accessible format.

### Project Objectives

The main objectives of this project were to:

- Evaluate overall sales performance using key performance indicators.
- Understand sales distribution across channels, regions, products, and outlet tiers.
- Examine the relationship between sales performance and collection efficiency.
- Identify collection gaps and potential receivables risks.
- Determine the product categories and manufacturers contributing most to sales.
- Assess sales target attainment and highlight the need for further performance investigation.
- Translate dashboard findings into actionable recommendations for management.
- Demonstrate the use of Power BI for business intelligence, data analysis, and storytelling.

---

## 2. Executive Summary

The dashboard reports total net sales of **$249.30 million** and total gross sales of **$247.86 million**, alongside total quantity sold of 18,000 units and an average unit price of $13.85K.

However, the reported profit margin is only 0.58%, indicating that profitability requires further investigation. The dashboard also reports gross profit of approximately $1.44 million.

The collection analysis reveals another important concern. Confirmed collections stand at $117.66 million, compared with an outstanding amount of $131.65 million. The reported collection rate is 47.19%, indicating that collection performance warrants management attention.

Product analysis shows that Grains is the leading category by net sales, contributing approximately $76 million. Beverages follows at $34 million, while Cooking Essentials contributes $30 million. At manufacturer level, Tropical General Investments leads with approximately $76 million in net sales.

The sales channel analysis shows that Pharmacy and Wholesaler are the leading channels, contributing approximately $58 million and $56 million respectively.

Taken together, the dashboard highlights three areas requiring management attention:

- **Profitability:** Investigate the reported low profit margin and validate the underlying financial measures.
- **Collections:** Strengthen receivables monitoring and investigate the outstanding balance.
- **Sales concentration:** Understand the business's reliance on leading products, manufacturers, and sales channels while identifying opportunities to improve performance elsewhere.

These findings provide a starting point for targeted commercial and financial interventions. Further investigation of the underlying transaction data is necessary before drawing conclusions about the causes of the observed performance.

---

## 3. Dashboard Structure

The Power BI report contains three principal analytical pages.

### 3.1 Sales Performance Overview

This page provides a high-level view of sales performance.

**Key performance indicators include:**

| KPI | Reported value |
|---|---:|
| Total Net Sales | $249.30M |
| Total Gross Sales | $247.86M |
| Profit Margin | 0.58% |
| Total Quantity Sold | 18K |
| Average Unit Price | $13.85K |

**Visualisations include:**

- Sales trend by month.
- Total net sales by channel.
- Transaction-level or grouped sales details in a data table.
- Filters for order date, outlet tier, and region.

**Analytical purpose**

This page helps management assess the overall sales position, identify the channels contributing most to revenue, and explore how performance varies across reporting periods and business segments.

The date, outlet-tier, and regional filters allow users to investigate specific portions of the business rather than relying exclusively on aggregate figures.

### 3.2 Collection Risk Page

This page examines collection performance and outstanding balances.

**Key performance indicators include:**

| KPI | Reported value |
|---|---:|
| Confirmed Collection | $117.66M |
| Outstanding Amount | $131.65M |
| Overview Order Count | 855 |
| Collection Rate | 47.19% |

**Visualisations include:**

- Outstanding amount distribution by sales channel.
- A table showing business names, outstanding amounts, confirmed collections, and order counts.
- Filters for agent name, state, and region.

**Analytical purpose**

The page provides visibility into outstanding receivables and allows management to investigate collection performance across sales agents, locations, and regions.

It can support the identification of accounts requiring follow-up, provided the underlying customer-level figures and collection measures are validated.

### 3.3 Product and Outlet Performance

This page focuses on product sales, manufacturer contributions, outlet tiers, and target attainment.

**Key performance indicators include:**

| KPI | Reported value |
|---|---:|
| Total Net Sales | $249.30M |
| Total Gross Sales | $247.86M |
| Total Quantity Sold | 18K |
| Agent Sales Target Amount | $1.53bn |
| Target Attainment | 16.30% |
| Profit Margin | 0.58% |

**Visualisations include:**

- Net sales by product subcategory.
- Net sales by product category.
- Net sales by outlet tier.
- Top 10 manufacturers by net sales.
- Filters for channel, brand, and subcategory.

**Analytical purpose**

This page enables management to evaluate the contribution of individual products, categories, manufacturers, and outlet segments.

It also presents the reported sales target and target attainment figures, helping management identify the need to investigate the gap between current sales and the target.

---

## 4. Top Five Insights and Recommendations

### Insight 1: Reported Profit Margin Is Low

**Finding**

The dashboard reports:

- Total Net Sales: $249.30M.
- Total Gross Sales: $247.86M.
- Gross Profit: approximately $1.44M.
- Profit Margin: 0.58%.

The reported gross profit and margin indicate that profitability should be investigated alongside revenue performance.

High sales do not necessarily translate into strong profitability. A business may generate substantial revenue while retaining a small amount as profit because of product costs, discounts, distribution expenses, or other costs, depending on how profit is defined.

However, the meaning of the reported margin depends on the underlying DAX measure and financial definitions.

**Business implication**

Management should avoid evaluating performance using sales revenue alone. Profitability measures must be validated and interpreted alongside sales volume, product costs, pricing, and applicable expenses.

**Recommendation**

1. Validate the definitions of Total Net Sales, Total Gross Sales, Gross Profit, and Profit Margin.
2. Confirm that the sales and profit measures use compatible financial definitions.
3. Analyse profit contribution by product category, manufacturer, and sales channel.
4. Investigate whether discounting, product costs, or other expenses explain the reported margin.
5. Establish a validated profitability baseline before introducing margin-improvement targets.

**Priority:** High.

---

### Insight 2: Outstanding Receivables Exceed Confirmed Collections

**Finding**

The Collection Risk dashboard reports:

- Confirmed Collection: $117.66M.
- Outstanding Amount: $131.65M.
- Collection Rate: 47.19%.
- Overview Order Count: 855.

The outstanding amount is approximately $14.0 million higher than confirmed collections.

This indicates a material gap between the amount reported as outstanding and the amount confirmed as collected.

The figures alone do not establish whether the outstanding balances are overdue, how long they have remained unpaid, or whether the reported collection rate is calculated from the same population as the other KPIs.

**Business implication**

Outstanding receivables can place pressure on working capital and limit the cash available to support inventory purchases, distribution, and other operating activities.

A clearer understanding of the collection position can help management prioritise follow-up and improve cash-flow visibility.

**Recommendation**

1. Validate the outstanding amount and confirmed collection measures.
2. Create a customer-level receivables report with outstanding balance, payment status, and last payment date.
3. Introduce ageing categories, such as 0–30, 31–60, 61–90, and over 90 days, using actual invoice due dates.
4. Prioritise follow-up based on outstanding balance, days overdue, and customer payment history.
5. Review collection performance by agent, state, region, and sales channel.
6. Monitor collection rates and overdue balances regularly.

**Priority:** Very high.

---

### Insight 3: Sales Are Concentrated in Particular Product Categories

**Finding**

The Product and Outlet Performance dashboard reports the following leading categories:

| Product category | Approximate total net sales |
|---|---:|
| Grains | $76M |
| Beverages | $34M |
| Cooking Essentials | $30M |
| Noodles | $18M |
| Baby Care | $16M |
| Home Care | $15M |

Grains is the leading category in the displayed category analysis, followed by Beverages and Cooking Essentials.

The displayed figures are rounded, so they should be treated as approximate values.

**Business implication**

The leading categories represent important contributors to reported sales. However, revenue contribution alone does not establish profitability, customer demand, or inventory efficiency.

Management needs to understand whether the leading categories also deliver attractive margins and whether weaker categories are underperforming because of low demand, distribution gaps, pricing, or other factors.

**Recommendation**

1. Compare sales and gross profit by category.
2. Analyse product demand across channels and outlet tiers.
3. Investigate the availability and distribution of leading products.
4. Review the performance of lower-contributing categories before making stocking or promotional decisions.
5. Identify opportunities to improve sales of underperforming products where demand and margins justify intervention.

**Priority:** High.

---

### Insight 4: Pharmacy and Wholesaler Are Leading Sales Channels

**Finding**

The Sales Performance Overview reports the following approximate net sales by channel:

| Sales channel | Approximate net sales |
|---|---:|
| Pharmacy | $58M |
| Wholesaler | $56M |
| Supermarket | $46M |
| HoReCa | $45M |
| Retail | $45M |

Pharmacy and Wholesaler lead the displayed channel comparison.

The figures suggest that these channels are important contributors to the company's reported sales.

**Business implication**

Differences in channel performance may reflect differences in customer demand, outlet coverage, order frequency, product mix, pricing, or distribution effectiveness.

The dashboard identifies where sales are concentrated but does not independently establish why the differences exist.

**Recommendation**

1. Investigate the factors driving Pharmacy and Wholesaler performance.
2. Compare gross profit and collection performance across channels.
3. Evaluate the performance of individual outlets within each channel.
4. Assess whether lower-contributing channels have growth opportunities.
5. Use channel-level performance data to inform sales coverage and distribution planning.

**Priority:** Medium to high.

---

### Insight 5: Sales Target Attainment Requires Investigation

**Finding**

The Product and Outlet Performance dashboard reports:

- Agent Sales Target Amount: $1.53bn.
- Target Attainment: 16.30%.

The reported attainment figure suggests that actual performance is below the target represented in the dashboard.

However, the actual sales amount used in the attainment calculation, the target period, and the aggregation method are not visible in the screenshots.

**Business implication**

A low target-attainment figure may indicate a performance gap, but management needs to establish whether the comparison is appropriate.

For example, an annual target should not be compared directly with sales recorded for only part of the year without accounting for the reporting period.

**Recommendation**

1. Validate the target-attainment formula.
2. Confirm that actual sales and targets cover the same period.
3. Compare performance by agent, region, channel, and product category.
4. Investigate whether underperformance relates to coverage, demand, product availability, or target-setting assumptions.
5. Develop realistic improvement plans based on validated performance gaps.

**Priority:** High, subject to target and reporting-period validation.

---

## 5. Additional Product and Manufacturer Findings

### 5.1 Leading Manufacturer

The manufacturer chart identifies Tropical General Investments as the leading manufacturer, with approximately $76 million in net sales.

The next displayed manufacturers include:

| Manufacturer | Approximate net sales |
|---|---:|
| Tropical General Investments | $76M |
| Dufil Prima Foods | $29M |
| PZ Wilmar | $20M |
| Hayat Kimya | $14M |
| Rite Foods | $10M |

Other manufacturers are displayed with smaller sales contributions.

**Recommendation**

Investigate manufacturer-level sales alongside product costs, gross profit, product availability, and customer demand. This will help distinguish high-revenue manufacturers from those delivering the strongest financial returns.

### 5.2 Leading Product Subcategories

The subcategory visual indicates that Rice contributes approximately $76 million in net sales, followed by Vegetable Oil at approximately $30 million and Instant Noodles at approximately $18 million.

The chart also displays other subcategories, including Diapers, Detergent, Corned Beef, Chocolate Drink, Tomato Paste, Evaporated Milk, and Energy Drink.

**Recommendation**

Evaluate subcategory performance using a combination of sales, profitability, volume, and outlet coverage. Revenue rankings can help identify important product groups, but they should not be the sole basis for inventory or pricing decisions.

### 5.3 Sales Distribution Across Outlet Tiers

The outlet-tier chart shows the following approximate shares of net sales:

| Outlet tier | Share of net sales |
|---|---:|
| Tier 3 | 30.11% |
| Tier 2 | 28.39% |
| Tier 1 | 22.76% |
| Tier 4 | 18.73% |

Tier 3 has the largest displayed share, followed by Tier 2.

**Recommendation**

Compare sales growth, profitability, order frequency, and collection performance across tiers. This will help determine whether the largest sales contribution also corresponds to the best overall commercial performance.

---

## 6. Answers to Key Business Questions

The dashboard was designed to support management questions across sales, collections, and product performance.

### Question 1: What is the overall sales performance?

The dashboard reports total net sales of $249.30 million, total gross sales of $247.86 million, and total quantity sold of 18,000 units.

The reported profit margin of 0.58% requires further validation to establish whether the business is generating an appropriate return on its sales.

### Question 2: Which sales channels contribute the most revenue?

Pharmacy leads the displayed channel analysis at approximately $58 million, followed by Wholesaler at approximately $56 million.

Supermarket, HoReCa, and Retail each contribute approximately $45–46 million.

These results identify important revenue-generating channels for further analysis.

### Question 3: Which product categories generate the highest sales?

Grains leads the displayed category analysis at approximately $76 million. Beverages and Cooking Essentials follow at approximately $34 million and $30 million respectively.

These categories should be investigated further to understand their profitability, demand, and contribution to overall business performance.

### Question 4: What is the current collection position?

The dashboard reports confirmed collections of $117.66 million and outstanding amounts of $131.65 million.

The reported collection rate is 47.19%.

The difference between confirmed collections and outstanding balances makes receivables monitoring a priority. Additional analysis is required to identify overdue balances and determine the causes of collection delays.

### Question 5: Which manufacturer contributes the most to sales?

Tropical General Investments leads the displayed manufacturer analysis at approximately $76 million in net sales.

This identifies the manufacturer as an important contributor to the reported sales total, although profitability and product-level performance should also be considered.

### Question 6: Are sales targets being achieved?

The dashboard reports target attainment of 16.30% against a displayed agent sales target amount of $1.53 billion.

This suggests a possible target-performance gap. The actual sales amount used in the calculation, target period, and measure definition should be validated before drawing a definitive conclusion.

### Question 7: How does sales performance change over time?

The Sales Performance Overview includes a monthly net sales trend.

However, the displayed month labels are not presented in clear chronological order. A reliable month-by-month conclusion should therefore be drawn only after confirming that the date field is correctly sorted and that the visual represents the intended reporting period.

### Question 8: Which outlets require collection follow-up?

The Collection Risk page includes a table of business names, outstanding amounts, confirmed collections, and order counts.

This is intended to support outlet-level investigation. However, the displayed table appears to repeat the same aggregate values across many business names. The customer-level calculations and visual aggregation must be corrected or validated before using the table to identify individual high-risk outlets.

---

## 7. Priority Interventions

Based on the findings, the following interventions are recommended.

| Priority | Intervention | Reason | Suggested monitoring measure |
|---|---|---|---|
| 1 | Validate financial measures | The reported sales, gross profit, and margin need reconciliation. | Reconciled sales, gross profit, and margin |
| 2 | Investigate outstanding receivables | Outstanding amounts exceed confirmed collections. | Outstanding balance and overdue receivables |
| 3 | Improve outlet-level collection visibility | The displayed customer table requires validation. | Verified outstanding balance by outlet |
| 4 | Investigate target attainment | Reported attainment is 16.30%. | Target attainment by agent and period |
| 5 | Evaluate product profitability | Leading categories may not necessarily be the most profitable. | Gross profit and margin by category |
| 6 | Assess channel performance | Pharmacy and Wholesaler lead reported sales. | Sales, margin, and collection rate by channel |
| 7 | Improve trend analysis | Monthly labels are not displayed chronologically. | Correctly sorted monthly sales trend |

### Immediate Action Plan

**Phase 1: Data and measure validation**

- Reconcile sales totals against the source data.
- Confirm the definitions of net sales, gross sales, gross profit, and profit margin.
- Validate collection and target-attainment calculations.
- Investigate repeated customer-level totals in the Collection Risk table.
- Correct the month sorting in the sales trend.

**Phase 2: Commercial and financial investigation**

- Identify overdue receivables and prioritise collection follow-up.
- Compare product categories by sales and profitability.
- Investigate the performance of leading sales channels.
- Analyse target attainment by agent and region.

**Phase 3: Monitoring and decision support**

- Establish regular reporting for sales, profit, collections, and target attainment.
- Compare current performance with previous periods using consistent definitions.
- Use validated results to guide pricing, sales coverage, collection follow-up, and distribution decisions.

---

## 8. Methodology

The project uses a business intelligence workflow to convert sales-related data into an interactive analytical report.

The methodology described below reflects the analytical structure visible in the dashboard. Specific data-cleaning operations and transformation steps should be documented from the actual Power Query workflow.

### 8.1 Business Understanding

The analysis was organised around three business areas:

- Sales performance.
- Collection risk.
- Product and outlet performance.

These areas guided the selection of KPIs, charts, filters, and business questions.

### 8.2 Data Preparation

The dashboard contains fields relating to dates, regions, channels, brands, categories, subcategories, outlet tiers, manufacturers, agents, states, and business names.

The underlying dataset should be prepared to ensure that:

- Dates are stored using appropriate date data types.
- Numeric measures use suitable numeric formats.
- Category and channel labels are standardised.
- Missing values and duplicate records are investigated.
- Sales, payment, and collection records are represented consistently.
- Relationships between relevant tables are correctly defined.

**Note:** These are recommended validation steps. They should only be reported as completed cleaning operations if they were actually performed.

### 8.3 KPI Development

The report displays measures for:

- Total Net Sales.
- Total Gross Sales.
- Gross Profit.
- Profit Margin.
- Total Quantity Sold.
- Average Unit Price.
- Confirmed Collection.
- Outstanding Amount.
- Overview Order Count.
- Collection Rate.
- Agent Sales Target Amount.
- Target Attainment.

The underlying formulas should be documented and validated to ensure that each KPI represents the intended business concept.

### 8.4 Data Visualisation

Different visual types were used to communicate different aspects of performance:

- **KPI cards:** Summarise important business metrics.
- **Line chart:** Displays monthly sales performance.
- **Horizontal bar charts:** Compare sales across channels, categories, subcategories, and manufacturers.
- **Donut charts:** Show the distribution of outstanding amounts across channels and sales across outlet tiers.
- **Tables:** Provide detailed views of sales and collection information.
- **Slicers:** Allow users to filter the report by available business dimensions.

### 8.5 Interactive Analysis

The report includes filters for relevant business dimensions, including:

- Order date.
- Outlet tier.
- Region.
- Sales agent.
- State.
- Channel.
- Brand.
- Product subcategory.

These controls allow users to investigate specific segments of the business and explore how the displayed metrics respond to their selections.

### 8.6 Insight Development

The analysis focuses on identifying:

- Major contributors to reported sales.
- Differences in performance across channels and product categories.
- Collection gaps.
- Potential target-attainment issues.
- Metrics that require additional validation.

Recommendations were developed from these findings, with additional investigation proposed where the dashboard does not establish the underlying cause of a performance difference.

---

## 9. Limitations and Areas for Improvement

A responsible analysis should distinguish between what the dashboard demonstrates and what still requires investigation.

### 9.1 Financial Measure Definitions

The screenshots display Total Net Sales of $249.30 million and Total Gross Sales of $247.86 million, alongside Gross Profit of approximately $1.44 million and Profit Margin of 0.58%.

These labels and figures require reconciliation.

In particular, the terms *gross sales*, *net sales*, and *gross profit* can represent different financial concepts. The underlying formulas and source data must be checked before the metrics are used for financial decisions.

### 9.2 Collection Rate Calculation

The dashboard reports confirmed collections of $117.66 million, outstanding amounts of $131.65 million, and a collection rate of 47.19%.

The collection-rate formula and its denominator are not visible in the screenshots.

A validated collection rate should use clearly defined amounts and a consistent population of invoices or receivables. Outstanding balances should also be distinguished from overdue balances.

### 9.3 Customer-Level Collection Table

The Collection Risk table displays repeated aggregate values for many business names.

This may indicate a problem with the measure's filter context, the relationship between tables, the granularity of the underlying data, or the way the visual is configured.

Until this is resolved, the table should not be relied upon to rank individual customers by collection risk.

### 9.4 Monthly Sales Sorting

The displayed month labels are not in chronological order.

Month names should be sorted by a numeric month field or an appropriate year-month key. Where multiple years are included, the analysis should distinguish the same month in different years.

This is important because an incorrectly sorted time-series chart can make sales trends difficult to interpret.

### 9.5 Target Attainment

The report displays a target attainment of 16.30% and an agent sales target amount of $1.53 billion.

The screenshots do not establish the exact actual-sales measure, target period, or aggregation method used in the calculation.

Further validation is required before interpreting the figure as a definitive measure of agent performance.

### 9.6 Limited Evidence of Causation

The dashboard identifies differences in sales, collections, and product contributions, but these differences do not independently explain why performance varies.

For example, lower sales may be associated with demand, product availability, pricing, outlet coverage, or other factors that are not directly established by the displayed visuals.

Additional analysis and business context would be required to identify causes.

### 9.7 Missing Historical and Operational Context

The screenshots do not provide sufficient information to determine:

- Whether sales are growing or declining year over year.
- How long outstanding balances have remained unpaid.
- Which products have the highest profit margins.
- Whether the business has seasonal sales patterns.
- Whether collection performance is improving.
- Whether sales targets are realistic for the period being analysed.

These questions could be addressed by incorporating additional historical, operational, and financial information.

---

## 10. Future Improvements

The dashboard could be extended in several ways.

### Sales Analysis
- Add year-over-year and month-over-month growth measures.
- Include actual sales versus target by agent and region.
- Analyse sales and gross profit together.
- Introduce a product-level profitability view.

### Collection Analysis
- Add receivables ageing categories.
- Distinguish overdue balances from total outstanding balances.
- Include last payment date and invoice due date.
- Introduce validated customer-level collection rankings.
- Track collection performance over time.

### Product and Outlet Analysis
- Add sales growth by product category.
- Compare outlet tiers by profitability and collection performance.
- Analyse product contribution to total sales.
- Identify products with low sales but meaningful profitability or growth potential.

### Data Quality and Reporting
- Validate all financial measures against source records.
- Improve month sorting and date-table design.
- Confirm relationships between sales, outlet, product, agent, and payment tables.
- Document the DAX measures and business definitions.
- Add data refresh information and reporting-period indicators.

---

## 11. Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development, interactive reporting, and visual analysis |
| Power Query | Data preparation and transformation, where used |
| DAX | KPI calculations and analytical measures, where used |
| SQL | Source-data querying and validation, where used |
| GitHub | Project documentation and portfolio presentation |

The tools listed above describe the project environment and recommended supporting workflow. The actual use of each tool should be confirmed against the project files before treating every item as a completed project step.

---

## 12. Conclusion

This project demonstrates how Power BI can be used to explore sales performance, collection risk, and product contributions through an interactive management dashboard.

The analysis highlights several areas requiring attention, including the reported low profit margin, outstanding receivables, the concentration of sales in particular categories and channels, and reported sales target attainment.

The project also demonstrates an important principle of business intelligence: presenting metrics is only one part of the analytical process. Metrics must be validated, interpreted in context, and connected to decisions.

By combining sales analysis, collection monitoring, and product performance reporting, the dashboard provides a foundation for further investigation and more informed commercial decision-making.

The next step is to validate the underlying measures and data relationships, resolve the identified reporting issues, and extend the analysis with profitability, receivables ageing, and historical performance indicators.

---

## 13. Project Deliverables

The project includes:

- An interactive Power BI report.
- A Sales Performance Overview page.
- A Collection Risk page.
- A Product and Outlet Performance page.
- KPI cards and comparative visualisations.
- Interactive filters for business dimensions.
- Business insights and recommendations.
- Documentation of analytical limitations and proposed improvements.


This project reflects my interest in using data analytics to understand business performance, uncover actionable insights, and support evidence-based decision-making.
