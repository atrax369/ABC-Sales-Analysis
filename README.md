# ABC-Sales-Analysis
ABC analysis on product sales to categorize inventory and optimize stock.
Product Sales Analysis – ABC Analysis

This project analyzes the annual sales value of products and classifies them using ABC analysis. The goal is to identify the most impactful products and optimize resource allocation.

Features

Calculates annual sales value for each product (quantity × price).

Determines each product’s percentage contribution (%) and cumulative percentage (%) using Excel formulas.

Categorizes products into ABC classes:

A: High-priority products (≈80% of total sales)

B: Medium-priority products (≈15% of total sales)

C: Low-priority products (≈5% of total sales)

Formulas Used

Percentage (%)

=D2/$D$12*100%


Cumulative (%)

=SUM($E$2:E2)


ABC Category

=IFS(F2<0.8,"A",F2<0.95,"B",TRUE,"C")

How to Use

Clone the repository:

git clone <repo-link>


Open the Excel file and enter product data.

Formulas will automatically calculate the percentage, cumulative percentage, and ABC category for each product.

Outcome

This analysis helps sales teams and managers to:

Identify top revenue-generating products

Allocate resources efficiently

Optimize sales strategy
