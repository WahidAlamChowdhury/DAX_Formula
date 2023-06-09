# DAX_Formula
DAX (Data Analysis Expressions) is a formula language used in Microsoft Power BI, Power Pivot, and Analysis Services. It allows you to create custom calculations, aggregations, and expressions within these tools. Here are some important formulas used in DAX:

SUM: Calculates the sum of a column or expression in a table.
Example: Total Sales = SUM(Sales[Amount])

AVERAGE: Calculates the average of a column or expression in a table.
Example: Average Price = AVERAGE(Products[Price])

COUNT: Counts the number of rows in a table or column.
Example: Number of Customers = COUNT(Customers[CustomerID])

MIN: Returns the minimum value from a column or expression in a table.
Example: Minimum Sales = MIN(Sales[Amount])

MAX: Returns the maximum value from a column or expression in a table.
Example: Maximum Sales = MAX(Sales[Amount])

IF: Performs a logical test and returns different values based on the result.
Example: Sales Category = IF(Sales[Amount] > 1000, "High", "Low")

CALCULATE: Modifies the filter context within a calculation.
Example: Total Sales in 2022 = CALCULATE(SUM(Sales[Amount]), Sales[Year] = 2022)

RELATED: Returns a value from a related table based on a relationship.
Example: Product Category = RELATED(Categories[CategoryName])

BLANK: Returns a blank value.
Example: Empty Field = BLANK()

DIVIDE: Divides two numbers and handles divide-by-zero errors.
Example: Sales per Customer = DIVIDE(SUM(Sales[Amount]), COUNT(Customers[CustomerID]))

These are just a few examples of important DAX formulas. DAX provides a wide range of functions for various calculations and data manipulations. Refer to the official Microsoft documentation for a comprehensive list of DAX functions and their usage.

