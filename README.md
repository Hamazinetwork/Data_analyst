

Problem Statement

The dashboard and analysis presented below are derived from a supermarket dataset. The primary objective of this analysis is to gain insights into the supermarket’s sales performance by examining key metrics such as product line quantity sold, branch-specific sales, payment methods, gender-based sales, city-wise sales, total quantity sold, Cost of Goods Sold (COGS), total profits, and overall sales. Additionally, an interactive slicer was implemented to enable dynamic exploration of the data, allowing users to filter the quantity sold by product line, date, branch, and payment method. These insights will empower the supermarket to make informed decisions regarding inventory management, cost efficiency, and the discovery of new revenue streams.

Steps Taken

•	Data Importation:

o	Imported the CSV file into Excel for data manipulation and analysis.

•	Data Transformation and Cleaning:

o	Utilized Power Query Editor to ensure data quality and consistency:

  	Checked Column Quality: Assessed the dataset for errors, missing values, and inconsistencies.

  	Removed Empty Rows: Eliminated irrelevant data to maintain dataset integrity.

  	Changed Data Types: Converted data into appropriate formats to ensure accuracy in calculations.

  	Merged Columns: Combined relevant columns to reduce data redundancy and streamline analysis.

•	Data Analysis:
![Excel h](https://github.com/user-attachments/assets/3a4d677b-7ecc-4cef-b5c3-1705a4da12de)
o	Leveraged pivot tables, aggregate functions, and text functions for data analysis:

  	Product Line Analysis: Created a column chart by using a pivot table to compare quantity sold against product line, dragging the product line to the Axis (Category) field and quantity sold to the Values field.
![sales by product line](https://github.com/user-attachments/assets/8e117b11-725a-4fac-9640-cba92c2a18f6)

  	Branch Sales Analysis: Used a pivot table to compare quantity sold by branch, creating a doughnut chart by dragging the branch to the Axis (Category) field and quantity sold to the Values field.
![doughnut chart](https://github.com/user-attachments/assets/4be7a6e5-2266-485c-b381-4fa794f45dc8)

  	Payment Method Analysis: Determined sales by payment type using a pivot table, dragging payment type to the Axis (Category) field and sales to the Values field to create a bar chart.
![sales by payment type](https://github.com/user-attachments/assets/c64b0f7e-21e3-4f5c-b9af-edc8e2247a3c)

  	City Sales Analysis: Analyzed sales against city using a pivot table, creating a column chart by dragging the city to the Axis (Category) field and sales to the Values field.
![sales by city](https://github.com/user-attachments/assets/6f468ab6-a28c-4aee-ad4b-3c29258265d2)

  	Gender and Payment Method Analysis: Used the SUMIFS function to calculate the sum of sales for each payment method by gender. This involved locking the gender column with absolute referencing while using relative referencing for the payment method row. The total sales for males and females were calculated using the SUM function, and these values were used to determine the percentage of sales by gender for each payment method. A column chart was then created to visualize this information.
![sales by gender and payment](https://github.com/user-attachments/assets/679622de-a91b-453a-a03e-986c61c2c14d)

•	Data Visualization and Reporting:

o	Developed an intuitive dashboard with visual elements such as column charts, doughnut charts, bar charts, and slicers.

o	Designed the visualizations to be easily interpretable, allowing stakeholders to quickly grasp essential insights.

o	Implemented dynamic slicers to facilitate real-time filtering and exploration of data, enhancing the interactivity of the report.

![Excel g](https://github.com/user-attachments/assets/be82d87e-7d0b-49f3-bd56-0d06f7920136)

Conclusion From the Analysis

The analysis yielded several actionable insights:

•	Top-Selling Product Line: Health & Beauty products had the highest sales volume, indicating strong consumer demand.

•	Preferred Payment Method: Cash was the most commonly used payment method, reflecting customer preference for traditional payment options.

•	Customer Demographics: Female customers made more purchases than male customers, highlighting potential opportunities for targeted marketing.

•	Top-Performing City: Naypyitaw recorded the highest sales figures, suggesting it as a key market for future expansion and targeted promotional efforts.

•	Best-Selling Branch: The sales distribution across branches was nearly equal, indicating consistent performance across different locations.

•	Strategic Recommendations: Based on these insights, the supermarket can optimize its inventory by focusing on high-demand product lines, explore cost-saving measures, and consider new marketing strategies to boost sales and profitability.
