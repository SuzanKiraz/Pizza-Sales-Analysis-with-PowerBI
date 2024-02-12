# Pizza-Sales-Analysis-with-PowerBI

This report is based on the data of a pizza company sales and orders in 2015. The goal is to analyze the data and gain insights on the given year. This project is completed using Power BI with Dax calculations. Let's dive into the world of pizza...

## About Data Set

Dataset is from https://www.kaggle.com/datasets/neethimohan/maven-pizza-challenge-dataset. The dataset has 5 .csv files and 4 tables.

- The order_details tables has 48621 rows containing order details regarding pizza type and order quantity.
- The orders table record the datetime indicators of the 21351 orders.
- The pizza_types table specifies the category, ingredients information about the 33 different pizza types offered by the pizza place.
- The pizzas table has 97 rows containing the pricing details of pizza based on the size and pizza type.

## Features

- order_id: Unique identifier for each order placed by a table
- order_details_id: Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)
- pizza_id: Unique key identifier that ties the pizza ordered to its details, like size and price
- quantity: Quantity ordered for each pizza of the same type and size
- order_date: Date the order was placed (entered into the system prior to cooking & serving)
- order_time: Time the order was placed (entered into the system prior to cooking & serving)
- unit_price: Price of the pizza in USD
- total_price: unit_price * quantity
- pizza_size: Size of the pizza (Small, Medium, Large, X Large, or XX Large)
- pizza_type: Unique key identifier that ties the pizza ordered to its details, like size and price
- pizza_ingredients: ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, unless another sauce is specified)
- pizza_name: Name of the pizza as shown in the menu
