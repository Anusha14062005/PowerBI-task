Problem Statement
The given sales dataset contained issues such as incorrect data types, duplicate order records, and missing analytical columns. The objective was to clean and transform the data using Power Query and prepare it for sales analysis.

The tasks included changing the data types, removing duplicate orders, creating date-related columns, calculating profit, classifying sales performance, filtering regional data, sorting sales values, editing formulas, and calculating category-wise total sales.

Solution Performed
The following data-cleaning and transformation operations were completed using Power Query:

Changed the Order_Date column data type to Date.

Converted numeric columns into suitable data types:

Integer-based columns were changed to Whole Number.

Sales and financial columns were changed to Decimal Number.

Removed duplicate records by using Order_ID as the unique identifier. This ensured that each order appeared only once.

Created the following columns from Order_Date:

Year

Month

Quarter

Created a custom column named Profit using the formula:

text
[Total_Sales] * 0.20
This calculated profit as 20% of the total sales.

Created a conditional column named Sales Performance using sales thresholds:

High sales → High

Average sales → Medium

Low sales → Low

Filtered the dataset to display records from the South region only.

Sorted the Total_Sales column in descending order, displaying the highest sales values first.

Edited the Profit calculation through the Advanced Editor and modified the formula according to the required calculation logic.

Used the Group By feature to calculate the total sales for each Category.

Result
The raw sales data was successfully cleaned, organized, and transformed into a structured dataset. The final output can now be used to analyze yearly, monthly, quarterly, regional, category-wise, and performance-based sales information more effectively.
