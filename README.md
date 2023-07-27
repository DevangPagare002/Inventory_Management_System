Name: Devang Dinesh Pagare

# Inventory_Management_System
This is my 1st Assignment in Python for the ML/AI Internship under Elitetechnogroup. The name of this assignment is Inventory_Management_System.

## About Repository

This repository contains an Inventory_Management_System for any general shop. It has 1 Python notebook and 3 .json files. They are:

  1. Inventory_Management_System.ipynb - Here the whole code exists. Users can buy items from shop/inventory or can sell items to shop/inventory.
  2. IMS_record.json - This file contains all the product records. If the user buys something from the shop/inventory, the records automatically get updated and the quantity of that product decreases. Similarly, If the user sells something to the shop/inventory, records automatically get updated and the quantity of that product increases. If the product which the user is selling to the inventory is new, the program will add that new product to the inventory.
  3. Sales.json - This file contains tracks all the sales made by the shop with the user. It contains records of products the user purchased along with bills, dates, and times.
  4. purchases.json - This file contains tracks of all purchases the shop did by the user. It contains records of product users sold to the shop along with bills, dates, and times.

## How Inventory works?

1. We start with pre-registering 30 product records. Those records are then stored in the IMS_record.json file.
2. Users can buy items from the shop or sell items to the shop.
3. If a user buys an item from inventory, the transaction will be registered in the Sales.json file.
4. If the user sells something to the shop/inventory, the transaction will be registered in the purchases.json file.
5. While buying the product, the user will be provided with the menu and the user is supposed to type the product ID of the desired product from the menu.
6. User can also buy the item in more than one quantity. 
7. When a user wants to sell items to the shop, the user is supposed to type product ID, name, price, quantity, weight, and color. If the product is completely new, then the program will add this product to the inventory with all the attributes the user types. If the product is not new, then we will just increase the quantity of the product in the inventory. In both cases, as the shop is purchasing something, so purchase record will be generated.

## About me:
Hello everyone, I am Devang Pagare, a Second-year B.Tech student at G.H. Raisoni College of Engineering and Management, Pune. I am passionate about AI, Machine learning, and Data Science.

## Contact me on:

Email: devpagare002@gmail.com

Linkedin: linkedin.com/in/devang-pagare
