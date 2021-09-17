Name: Devang Dinesh Pagare

# Inventory_Management_System
This is my 1st Assignment of Python for ML/AI Internship under Elitetechnogroup. Name of this assignment is Inventory_Management_System.

## About Repository

This repository contains an Inventory_Management_System for any general shop. It has 1 Python notebook and 3 .json files. They are:

  1. Inventory_Management_System.ipynb - Here the whole code exists. User can buy items from shop/inventory or can sell items to shop/inventory.
  2. IMS_record.json - This file contains all the product records. If the user buy something from the shop/inventory, the records automatically gets updated and quantity of that product decreases. Similarly, If the user sells something to the shop/inventory, records automatically gets updated and quantity of that product increases. If the product which user is selling to the inventory is new, the program will add that new product into the inventory.
  3. Sales.json - This file contains tracks all the sales made by shop with the user. It contains records of products user purchased along with bill, date and time.
  4. purchases.json - This file contain tracks of all purchases shop did from the user. It contains records of product user sold to the shop along with bill, date and time.

## How Inventory works?

1. We start with pre-registering 30 product records. Those records are then stored in IMS_record.json file.
2. User can buy items from shop or sell items to the shop.
3. If user buys item from inventory, the transaction will be registered in Sales.json file.
4. If user sells something to the shop/inventory, the transaction will be registered in purchases.json file.
5. While buying the product, user will be provided with the menu and user is supposed to type the product ID of the desired product from the menu.
6. User can also buy the item in more than one quantity. 
7. When user wants to sell items to the shop, user is supposed to type product ID, name, price, quantity, weight and color. If the product is completely new, then program will add this product in the inventory with all the attributes user typed. If product is not new, then we will just increase the quantity of the product in the inventory. In both of the cases, as shop is purchasing something, so purchasse record will be generated.

## About me:
Hello everyone, I am Devang Pagare, Second year B.Tech student at G.H. Raisoni College of Engineering and Management, Pune. I am passionate about AI, Machine learning and Data Science.

## Contact me on:

Email: devpagare002@gmail.com

Linkedin: linkedin.com/in/devang-pagare-90a12a219
