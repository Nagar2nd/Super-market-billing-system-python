# Supermarket Billing System

## Project Overview

The **Supermarket Billing System** is a Python-based application designed to streamline the billing process in a supermarket. It processes multiple items, calculates total prices, applies discounts based on predefined conditions, and generates an itemized receipt for the customer. This interactive system is built to ensure accurate and efficient billing.

## Features

- **Multiple Item Processing:** Allows users to input multiple items with quantities in a single transaction.
- **Discount Application:** Automatically applies discounts based on the total amount:
  - 5% for totals up to ₹500
  - 7% for totals up to ₹1000
  - 15% for totals up to ₹5000
  - 20% for totals above ₹5000
- **Itemized Receipt:** Provides a detailed receipt showing each item, price, quantity, subtotal, discount, and final total.
- **Customer Details:** Captures and displays customer name and phone number for each transaction.
- **Continuous Input:** Processes multiple transactions for consecutive customers in a single run.

## How It Works

1. **Customer Information:**
   - The system prompts for the customer's name and phone number.
   
2. **Item Selection:**
   - A list of available products and prices is displayed.
   - Customers enter the item name and quantity. The system calculates the subtotal and adds the item to the cart.
   
3. **Discount Calculation:**
   - The system applies discounts based on the total bill amount:
     - 5% discount for totals up to ₹500
     - 7% discount for totals up to ₹1000
     - 15% discount for totals up to ₹5000
     - 20% discount for totals above ₹5000

4. **Receipt Generation:**
   - An itemized receipt is generated, displaying:
     - Store information, date, and time
     - Customer name and phone number
     - Itemized details (name, price, quantity)
     - Total bill, discount applied, and the final bill after the discount

5. **Multiple Transactions:**
   - The program can handle consecutive customers in a single run, asking after each receipt whether there is another customer in the queue.

## Technologies Used

- **Python 3.x** for the core logic and implementation.
- **Datetime Module** for generating the current date and time on receipts.
