# E-commerce-Performance-Analysis

Description:
This analysis aims to address potential challenges and opportunities within the e-commerce business. By analyzing historical data and identifying key trends and patterns, this project will provide valuable insights to guide strategic decision-making and drive continuous improvement within the e-commerce business.

Objective:
To gain a comprehensive understanding of the e-commerce business's current performance and identify key areas for improvement in sales, customer retention, and operational efficiency.

Goal:
To drive sustainable business growth and enhance overall profitability by leveraging data-driven insights.

Data Cleaning Summary: Microsoft Excel
•	Blank Cells: Checked for blank cells using the COUNTBLANK function. No blank cells were found.
•	Errors: Checked for errors using the ISERROR function. No errors were found.

Data Corrections: 
o	Spelling Errors: 
	Corrected 20 instances of "furnitures" to "furniture."
	Corrected 13 instances of "tech" to "technology."
	Corrected 27 instances of "late" to "late delivery."
	Corrected 23 instances of "home" to "home office."

Power BI 
Sales Trend Analysis
•	Visualization: Line Chart (Order Date vs. Sum of Sales per Order)
•	Findings: 
o	Upward sales trend observed over the years.
o	Significant sales growth after 2018.
o	Slight sales decline after 2021.
Category Revenue Performance
•	Revenue Calculation: Created a calculated column using the format "Revenue" = (Sales per order * Order Quantity - Order Item Discount) 
•	Top Revenue Categories: 
o	Office Supplies: 28.91M (59% contribution)
o	Furniture: 11.47M (23% contribution)
o	Technology: 8.79M (18% contribution)
•	Visualization: Card visuals for revenue per category, and a slicer to filter by category to show each of the category revenue contribution.
Regional Sales Performance
•	Visualization: Clustered Bar Chart (Customer Region vs. Sum of Sales per Order)
•	Findings: 
o	West: Highest sales (8.1M)
o	East: Second highest sales (7.2M)
o	Central: Third highest sales (5.9M)
o	South: Lowest sales (4.1M)
•	Factors: Sales differences primarily attributed to varying customer bases in each region, particularly the number of retained customers. 
o	West: 39.43k customers, 42% retention
o	East: 35.06k customers, 39% retention
o	Central: 28.54k customers, 34% retention
o	South: 20.03k customers, 28% retention
Delivery Status Impact
•	Visualization: Stacked Bar Chart (Delivery Status vs. Sum of Sales per Order)
•	Findings: 
o	Late Delivery: Highest impact on sales (13M)
o	Advanced Shipping: 6M
o	On-Time Shipping: 5M
o	Shipping Cancelled: 1M
Customer Segmentation
o	Consumer: 63.80k
o	Corporate: 37.30k
o	Home Office: 21.96k

•	Customer Retention: 
o	Overall Retention Rate: 71%
o	Consumer: 55%
o	Corporate: 40%
o	Home Office: 29%
•	Visualization: Card visual for customer segment distribution.
Shipping Type Analysis
•	Visualization: Gauge visuals for each shipping type (Standard, Second Class, First Class, Same Day) to visualize their impact on delivery performance.
Findings: 
o	Standard Class: Highest impact (71.84k)
o	Second Class: 24.46k
o	First Class: 20.43k
o	Same Day: 6335
Slicers:
•	Category Name: Filter visualizations by product category.
•	Customer Region: Filter visualizations by customer region.
•	Customer Segment: Filter visualizations by customer segment

Key Observations
•	Sales have shown significant growth since 2018, with a slight decline observed after 2021.
•	Office Supplies is the top-performing category, contributing significantly to overall revenue.
•	Sales performance varies significantly across regions, with the West region leading the way.
•	While "Late Delivery" appears to have the highest sales volume, it likely indicates operational inefficiencies; it did not have the highest customer retention rate, this indicates customer dissatisfaction, which can negatively impact customer loyalty and brand reputation in the long term.
•	The Consumer segment demonstrates the largest customer base and retention rate.  
•	Standard Class is the most popular shipping type.

Solutions
•	Capitalize on the success of Office Supplies. Explore opportunities for product expansion, cross-selling, and upselling within this category.
•	Implement strategies to replicate successful strategies from the West region in other regions.
•	Focus on retaining and growing the Consumer segment. Implement targeted marketing campaigns, loyalty programs, and personalized offers to retain existing customers and attract new customers.
•	Monitor customer feedback and satisfaction levels related to shipping options to identify areas for improvement.

Key Recommendations
•	Investigate the factors contributing to the post-2021 decline.
•	Implement robust tracking and monitoring systems to identify and address the root causes of late deliveries proactively.
•	Prioritize customer satisfaction by addressing customer concerns and improving the overall customer experience



