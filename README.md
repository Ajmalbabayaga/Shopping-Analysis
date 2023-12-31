# Shopping-Analysis

Introduction:

The provided PySpark script is designed to analyze a shopping dataset containing information about customers, orders, products, and sales. The script uses various PySpark functions to perform data manipulations, aggregations, and visualizations to gain insights into different aspects of the shopping data. Below is a summary of the analytical tasks performed in the script:

1. *Least Sold Product in Each Month:*
   - Determines the least sold product in each month.
   - Displays the results in a bar graph showing the minimum quantity for each product in each month.

2. *Total Number of Deliveries in Each State:*
   - Calculates the total number of deliveries in each state.
   - Presents the results in a bar graph showing the delivery count for each state.

3. *Most Common Age Group Among Customers:*
   - Identifies the most common age group among customers.
   - Visualizes the customer count for each age group in a bar graph.

4. *Average Delivery Time and Orders with Shortest/Longest Delivery Times:*
   - Calculates the average time it takes for orders to be delivered.
   - Identifies orders with the shortest and longest delivery times.
   - Prints the average delivery time and details of orders with the shortest and longest delivery times.

5. *Total Sales or Revenue for Each Product Type:*
   - Calculates the total sales or revenue for each product type.
   - Displays the total revenue for each product type in a bar graph.

6. *Products with Low Inventory Levels:*
   - Identifies products with low inventory levels that need to be restocked.
   - Sets a threshold value, and products below this threshold are considered for restocking.
   - Displays the products and their quantity differences in a bar graph.

7. *Busiest Shopping Days of the Week:*
   - Determines the busiest shopping days of the week.
   - Presents the results in a bar graph showing the number of orders for each day of the week.

8. *Products Available in a Specific Size or Color:*
   - Allows the user to input a specific size and color.
   - Filters and displays products that match the specified size and color.

9. *Customers with Highest Purchase Amount:*
   - Identifies customers who have made the highest purchase amount.
   - Displays the top 10 customers by total purchase amount in a bar graph.

10. *Seasonal Trends in Product Sales:*
    - Analyzes whether there are seasonal trends in product sales.
    - Presents the monthly sales trends in a bar graph.

Conclusion:

The PySpark script provides valuable insights into various aspects of the shopping dataset, 
including product sales, customer demographics, delivery performance, and inventory levels. 
The visualizations, such as bar graphs, help in understanding trends and patterns in the data. 
Users can leverage the script to make informed business decisions, such as identifying popular products, 
optimizing inventory, and improving delivery processes. Additionally, the script demonstrates the power 
of PySpark for large-scale data processing and analysis in a distributed computing environment.
