# final-project
Sales Analysis

This was my final project as part of Concordia University's Data Science Diploma Program.

For a video demonstration, please see the 'Demonstration Video' file.

This project is a analysis of sales data conducted for Panier Quebecois, a Montreal startup that is an online farmer's market operating since 2020: https://panierquebecois.ca/en/

They shared sales data from 2020 to present in the form of a CSV file (not included). 

Panier Quebecois asked to answer a few business questions based on the sales data:
1 - What types of customers use promo codes? Are these high value customers? Repeat customers?
2 - What product categories are highest value?
2 - Which product categories in an order predict high-value customers? Which product categories help retain high-value customers?

The aim is to determine how effective current promo codes are, and to determine which product categories the company should offer more of in order to attract consistent, high-value customers.

To answer these questions, I used Pandas dataframes in Python Jupyter, and a mix of descriptive statistics, linear regression and logistic regression. 
These calculations are shown in 'Calculations - Promo Codes - Demo' and 'Calculations - Products - Demo'.
Neural nets were also attempted but not used in the final analysis, as explained near the end of 'Calculations - Products - Demo'.

In order to preserve company and customer privacy, I modified the code to remove all references to customer and employee information. For this reason, the CSV file with the raw data is also not included in the repository.

To present the findings, I used Dash by Plotly to build a presentation page. The code for this is in 'Plotly'. It will run a Dash App on a local server. A demonstration is in the 'Demonstration Video' file.
