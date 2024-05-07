# Restaurant-Delivery-Website

# Project Overview

In this project, we will develop a web server with endpoints to implement server-side logic for a restaurant's online ordering system. Adherence to our provided coding guidelines and submission requirements is essential.


# Problem Description

We will create a robust server-side application for a restaurant to manage customer orders from placement to delivery. The application will include the following functional components:

1. Restaurant Website
   - Pages and Functionalities:
     - Home Page:
       - Display our restaurant's name, location, and operating hours.
       - Showcase menu items with prices and descriptions.
     - Menu Page:
       - View categorized menu items (e.g., appetizers, main courses, desserts).
       - Select and add items to the order cart.
     - Order Page:
       - Place new orders by selecting items from the menu.
       - View order summary with total price.
     - Order History Page:
       - View past orders with details like order date, items, and status.
  
2. Order Processing Website
   - Pages and Functionalities:
     - Dashboard:
       - Display incoming orders with customer details and order status.
       - Update order status (e.g., received, ready for delivery, in transit, delivered).
     - Order Details Page:
       - View specific order details including customer information, ordered items, and delivery address.
     - Customer Search Page:
       - Search for orders by customer name or order ID for quick lookup.

3. Delivery Driver Website
   - Pages and Functionalities:
     - Driver Dashboard:
       - View available orders for delivery.
       - Select an order to deliver and update its status to in transit.
     - Delivery Confirmation Page:
       - Confirm delivery completion by updating the order status to delivered.
       - Upload a photo as proof of delivery.



### Database Requirements

We will utilize MongoDB for database implementation with the following collections:

- `orders_collection`:
  - Attributes: customer name, delivery address, ordered items, order date/time, and status.
- `drivers_collection`:
  - Attributes: username, password, full name, vehicle model, color, and license plate.
- `menu_items_collection`:
  - Attributes: name, image, description, and price for menu items.
