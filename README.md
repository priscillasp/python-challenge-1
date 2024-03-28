# Python Challenge 1 - Food Truck Menu 
## Purpose 
The purpose of this code is to provide the Variety Food Truck with an interactive ordering system that outputs a visually organized menu, sub-menu and receipt. 
## Features
* Interactive menu selection system.
* Input validation for menu selections and quantities.
* Formatted receipt output with calculated total cost.
## Getting Started
### Prerequistes 
* Python 3.x must be installed on your system to run this project. 

### Installation 
Clone the repository to your local computer:

```bash
git clone https://github.com/priscillasp/python-challenge-1.git
```

Navigate into the project directory: 
```bash
cd python-challenge-1
```

To start program and open up menu, run the following command in your terminal: 
```bash
python menu.py
```
## Usage 
After launching the program, you will be presented with a menu of items. Here's how to use the interactive Variety Food Truck Menu:
* Once you start the program you will receive a greeting and then asked which menu category you would like to order from (e.g. Snacks, Meals, Drinks and Dessert).
* Enter the number corresponding to your menu category choice when prompted.
    * if you enter a number that is not an option or anything other than a number you will be given an error message and asked "would you like to keep ordering?" Then you will be taken back to initial menu category list.
* Once you enter your number choice for menu category you will then be prompted to select which item from that menu category you would to order. 
    * The only valid input is also a number. If you do not enter a number you will be asked if you would like to keep ordering and then will be taken back to the initial menu category list. 
* Enter the quantity for the chosen item. 
    * If you enter an invalid quantity or press enter without input, the quantity will default to 1.
* After selecting the menu category, menu item and quantity, you'll be asked if you'd like to continue ordering. Enter 'y' to continue or 'n' to finish and print your receipt.
* The program will then display a formatted receipt that includes each item's name, price, and quantity, followed by the total cost of your order.

## Receipt Example 
```swift
Item name                 | Price  | Quantity
--------------------------|--------|----------
Chocolate lava cake       | $10.99 |   4
Burger - Chicken          | $7.49  |   2

Your total cost is $58.94
```
## Contributing 
Entire code was written by Priscilla Morales. However, I did ask classmates and chatgpt to help me understand certain requirements throughout the challenge. I took their guidance and applied it uniquely to my code. 

