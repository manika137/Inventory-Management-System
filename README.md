# Inventory-Management-System

This code is for the billing system for 30 pre-recorded items.
The record file saves the product ID, product name, cost and total quantity available.
The sales.json file saves the number of total purchases made by customers and also saves the total cost.
THE IMS.ipynb file contains the code to generate the bill and has the following functions: 
1. The user can enter the total number of items he wants to buy and the quantity of each item. The total cost is added with each purchase, number of purchases and number of products available updated.
2. If the quantity user wants to buy is more than that available, then an error message is generated.
3. Before billing, the user is asked to confirm if all purchases are done. If not, then the buying loop (point 1) starts again.
4. After the confirmation, the system generates a random purchase suggestion to the user(using random.randrange function)
5. According to the total bill cost, certain discount is provided to the costumer.
6.  
