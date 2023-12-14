# Virtual Coffee Machine

## Overview
This Python script simulates a virtual coffee machine that serves espresso, latte, and cappuccino. Users can choose a drink, insert virtual coins for payment, and the script checks if the machine has enough resources to make the drink. It also provides a report of the machine's current resources and earnings.

## Features
- **Multiple Drink Options**: Offers espresso, latte, and cappuccino.
- **Resource Management**: Checks if the machine has enough ingredients to make the chosen drink.
- **Coin Processor**: Simulates the insertion of coins and calculates total money inserted.
- **Transaction Validation**: Checks if the user has inserted enough money for the drink.
- **Making Coffee**: Deducts ingredients from the machine's resources after a successful transaction.
- **Reporting**: Displays the current resource levels and total profit.

## How to Play
1. Run the script to start the coffee machine.
2. Choose a drink by typing 'espresso', 'latte', or 'cappuccino'.
3. Insert virtual coins as prompted (quarters, dimes, nickles, and pennies).
4. The machine checks if you have inserted enough money and if it has the necessary resources.
5. If the transaction is successful, your chosen coffee is made, and change is returned if necessary.
6. Type 'report' to view the machine's current resources and profit.
7. Type 'off' to turn off the machine.

## Functions
- `is_resource_sufficient(order_ingredients)`: Checks if the machine has enough resources for the order.
- `process_coins()`: Simulates coin insertion and calculates the total value.
- `is_transaction_successful(money_received, drink_cost)`: Validates the transaction based on the money received.
- `make_coffee(drink_name, order_ingredients)`: Makes the coffee and updates the machine's resources.
- `MENU`: A dictionary containing details of the drinks.
- `resources`: A dictionary representing the machine's initial resources.

## Dependencies
- No external libraries are required.
- Requires `data.py` containing `MENU` and `resources` dictionaries.

## How to Run
Make sure Python is installed on your system. Place the script and `data.py` in the same directory and run the script.

## Note
This script is a simulation and does not involve real transactions or physical coffee making. It's an interactive way to learn resource management and basic Python programming.

---

Enjoy your virtual coffee experience!