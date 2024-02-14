# Pizza_Sales_Analysis
## Introduction
This Project provides in-depth insights into Pizza Sales data, where we utilize SQL for detailed data analysis and Power BI to craft interactive visualizations. This project delves into comprehensive insights on pizza sales, covering daily and monthly trends, sales categorized by pizza type and size, and pinpointing top-selling pizzas based on revenue, quantity, and total orders.

## Key Features

This pizza sales dataset make up 12 relevant features:

order_id: Unique identifier for each order placed by a table

order_details_id: Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)

pizza_id: Unique key identifier that ties the pizza ordered to its details, like size and price

quantity: Quantity ordered for each pizza of the same type and size

order_date: Date the order was placed (entered into the system prior to cooking & serving)

order_time: Time the order was placed (entered into the system prior to cooking & serving)

unit_price: Price of the pizza in USD

total_price: unit_price * quantity

pizza_size: Size of the pizza (Small, Medium, Large, X Large, or XX Large)

pizza_type: Unique key identifier that ties the pizza ordered to its details, like size and price

pizza_ingredients: ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, unless another sauce is specified)

pizza_name: Name of the pizza as shown in the menu

## Analysis
For the analysis, I utilized SQL and subsequently visualized the results using Power BI. The decision to employ SQL was driven by its capability to efficiently analyze datasets of varying sizes, enabling swift problem investigation and expedited generation of sales reports. The initial step involved uploading the dataset onto SQL Server, where I conducted comprehensive analysis before proceeding to visualize the insights using Power BI.


