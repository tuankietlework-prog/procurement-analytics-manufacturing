Procurement Spend & Supplier Risk Analysis

A procurement analytics case study for a manufacturing company using Excel to evaluate supplier performance, procurement KPIs and spending optimization.

1. Project Overview
Background

In procurement operations, tracking spend and evaluating supplier performance are essential for controlling costs, reducing supply chain risk, and improving decision-making. However, procurement data is often stored as individual transactions, which makes it difficult to consolidate, analyze, and extract meaningful insights.

This project was developed to build an Excel-based procurement analytics dashboard supported by Python for data cleaning and preparation. The analysis focuses on spend distribution, supplier performance, and supplier risk classification to support more informed procurement decisions.

Objectives
Analyze procurement spend by supplier and category.
Identify optimization opportunities through Pareto analysis.
Evaluate supplier performance and risk exposure.
Support procurement decision-making through an interactive dashboard.
2. Dataset
Item	Information
Data Source	Kaggle
Dataset Size	777 Purchase Orders
Number of Suppliers	5
Number of Categories	5
Tools Used	Excel, Python (Pandas)

The dataset includes the following fields:

Purchase Order ID
Supplier
Category
Order Date
Delivery Date
Spend
Savings
Compliance Rate
Defect Rate
Lead Time

This structure provides enough detail to analyze both financial performance and operational supplier behavior.

3. Data Preparation

Before analysis, the dataset was cleaned and standardized to ensure accuracy and consistency.

The preparation process included the following steps:

Checking for missing values.
Standardizing supplier names.
Validating order dates and delivery dates.
Calculating lead time.
Formatting the data for PivotTables and dashboard reporting.

Python (Pandas) was used to support data cleaning and validation, while Excel was used for the main analysis and visualization. This combination helped improve data quality and ensured the final dashboard was reliable and easy to update.

4. Spend Analysis
Supplier Spend

The spend analysis shows that procurement value is distributed relatively evenly across the five suppliers, with each supplier accounting for approximately 17% to 22% of total spend.

This indicates that procurement spend is not highly concentrated among a small number of suppliers, which means the organization does not fully follow a classic Pareto pattern. As a result, there may be limited leverage from supplier concentration alone, but there is still an opportunity to review sourcing strategy and explore order consolidation where appropriate.

Key Insights
No single supplier dominates total spend.
Spend is distributed fairly evenly across suppliers.
There is potential to improve negotiation leverage through supplier consolidation.
Procurement decisions should consider both spend value and supplier performance.
Pareto Analysis

A Pareto chart was used to assess whether a small number of suppliers account for most of the spend. The chart helps identify whether procurement value is concentrated or spread across multiple suppliers.

In this case, the cumulative spend curve does not show a steep 80/20 concentration. This suggests that procurement spend is relatively balanced, and supplier management should focus not only on cost but also on service quality, reliability, and risk exposure.

5. Category Analysis

Spend was also analyzed by category to identify the most significant purchasing groups.

Category-level analysis helps procurement teams:

Identify critical spending areas.
Monitor spend trends over time.
Support budgeting and sourcing decisions.
Prioritize categories for negotiation or supplier review.

Understanding spend by category is important because different categories may require different sourcing strategies. For example, high-value categories may need stronger supplier governance, while lower-value categories may be managed through standard purchasing processes.

6. Supplier Performance Analysis

Supplier performance was evaluated using the following metrics:

Total Spend
Savings
Lead Time
Compliance Rate
Defect Rate

These indicators provide a balanced view of supplier performance across cost, quality, and delivery reliability.

Interpretation of Metrics
Total Spend shows the financial importance of each supplier.
Savings reflects the value created through procurement efficiency.
Lead Time measures delivery speed and responsiveness.
Compliance Rate indicates how well suppliers follow procurement requirements.
Defect Rate reflects product or service quality issues.

A supplier with strong spend value may still create operational risk if lead time is inconsistent or defect rates are high. For this reason, supplier performance should be assessed using both financial and operational metrics.

7. Supplier Risk Assessment

To assess supplier risk, a composite risk score was developed using three criteria:

Defect Rate
Compliance Rate
Lead Time

These indicators were combined to create a risk profile for each supplier. The risk score was then compared with spend value to classify suppliers using the Kraljic Matrix.

Kraljic Matrix Interpretation

The Kraljic Matrix is a widely used procurement framework that categorizes suppliers based on two dimensions:

Supply risk
Profit impact or spend importance

Using this framework, suppliers can be grouped into four quadrants:

Strategic
Leverage
Bottleneck
Non-critical
Findings

The analysis identified two suppliers in the Strategic quadrant, meaning they represent both high spend and high risk. These suppliers require close monitoring, stronger governance, and contingency planning to reduce the risk of supply disruption.

Business Implications
Strategic suppliers should be managed through long-term collaboration and performance tracking.
Leverage suppliers can be optimized through competitive sourcing and negotiation.
Bottleneck suppliers require risk mitigation plans to avoid operational disruption.
Non-critical suppliers can be managed through standard procurement controls.
8. Dashboard

An Excel dashboard was built to visualize the key procurement metrics and support quick decision-making.

The dashboard includes the following components:

KPI Cards
Pareto Chart
Spend by Supplier
Spend by Category
Supplier Risk Matrix
The dashboard was designed to update automatically when the underlying data changes through PivotTables and formulas such as SUMIF, COUNTIF, and AVERAGEIF. This makes the report practical for ongoing procurement monitoring rather than a one-time analysis.

9. Recommendations

Based on the analysis, the following actions are recommended:

Review opportunities to consolidate orders and improve supplier negotiation power.
Monitor lead time, compliance rate, and defect rate on a regular basis.
Establish service-level agreements for suppliers in the Strategic quadrant.
Develop backup sourcing plans to reduce dependency risk.
Use the dashboard as a recurring procurement performance monitoring tool.

These recommendations are intended to improve both cost efficiency and supply chain resilience.

