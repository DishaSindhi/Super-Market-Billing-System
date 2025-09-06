# Super Market Billing System 

A simple **Python-based billing system** designed to simulate a supermarket checkout process. It allows customers to select items, specify quantities, automatically calculates totals, applies discounts, and generates a formatted bill/receipt.

##  Project Overview

This project demonstrates the use of **Python dictionaries, loops, and conditional statements** to create a basic billing system for supermarkets. It helps store owners manage product pricing, calculate total amounts, and apply discounts based on purchase value.

##  Features

* Interactive CLI (Command-Line Interface) for customer input
* Predefined list of products with prices
* Ability to add multiple items with specified quantities to the cart
* Automatic calculation of total cost and applicable discount
* Generates a formatted receipt with itemized details

##  How It Works

1. Customer enters their **name** and **phone number**.
2. The system displays a list of available products and prices.
3. The customer selects products and quantities to add to their cart.
4. The program calculates:

   * Total amount
   * Applicable discount (5%, 10%, 15%, or 20% depending on total)
   * Payable amount after discount
5. A formatted receipt is printed showing all purchased items, prices, and totals.

##  Discount Structure

| Total Amount (₹) | Discount Applied |
| ---------------- | ---------------- |
| ≤ 500            | 5%               |
| ≤ 1500           | 10%              |
| ≤ 3500           | 15%              |
| ≤ 5000           | 20%              |
| > 5000           | No Discount      |

##  Technologies Used

* **Python** (no external libraries required)

##  How to Run

1. Save the script as `supermarket_billing.py`.

2. Run it using Python:

   ```bash
   python supermarket_billing.py
   ```

3. Follow on-screen prompts to enter your name, phone number, select products, and view the bill.

##  Sample Output

```
--------------------------------------------------
Welcome to the Super Market Billing System
--------------------------------------------------
Name: Disha Sindhi
phone_number: 6543456763

Item name      Price      Quantity   Total
-------------------------------------------
Milk           30.0       2.0        60.0
Cooking oil    60.0       3.0        180.0
...
-------------------------------------------
final_amount: 1346.0
discount_applied: discount 10%
payable_amount: 1211.4
--------------------------------------------------
```

## 👤 Author

**Disha Sindhi**

* Email: [dishasindhi7@gmail.com](mailto:dishasindhi7@gmail.com)
* LinkedIn: [Disha Sindhi](https://www.linkedin.com/in/disha-sindhi-b0092732a)
* portfolio: [Disha Sindhi portfolio](https://www.wscubetech.com/portfolio/data/disha-sindhi-rsk7ymi)

