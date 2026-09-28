# Bi-Dashboard

Overview
An interactive Power BI dashboard built to analyze e-commerce sales performance, track revenue trends, and evaluate customer buying behavior across product lines.

The goal of this project was to clean messy underlying tables, establish a structured relational data model, and turn raw order logs into clear executive metrics.

Data Cleaning & Preparation
The dataset consists of two tables: customers and orders. Key data transformation steps included:

• Field Concatenation: Combined separate first_name and last_name columns into a unified customer_name field for cleaner reporting.
• Missing Value Imputation: Addressed missing values in customer engagement scores by creating a Clean Score field, setting nulls to 0.
• Data Formatting: Converted date text into proper order_date values and formatted sales figures into numerical currency representations.
• Relational Modeling: Built a 1-to-Many relationship connecting customers using customer_id.

Key Insights
• Top-Line Metrics: $103K in total revenue across 100 orders from 12 distinct customers.
• Category Dominance: Laptops account for over half of total revenue ($52K / 51.14%), followed by Smartphones ($24K) and Tablets ($19K).
• Top Product: The Dell XPS 15 generated the highest individual product revenue at $25K.
• Growth Trajectory: Consistent upward quarterly revenue trend from 2024 through 2026.

Tools Used
• Power BI Desktop (Data Modeling, Visualizations, Slicers)
• Power Query (Data Cleaning, Null Handling, Column Transformations)

Preview

<img width="1447" height="802" alt="Screenshot 2026-09-28 230614" src="https://github.com/user-attachments/assets/ba70fbf9-0f0d-47bb-b0ce-ebb0bbd32c69" />
<img width="1441" height="801" alt="Screenshot 2026-09-28 230637" src="https://github.com/user-attachments/assets/488f8139-21a9-4f00-8a14-0ac3f7ef20e2" />
