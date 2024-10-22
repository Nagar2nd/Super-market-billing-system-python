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

-------------------------------------------------------------------------------------------------------------------------------------------

## Sample Output :
Enter your name :  Shivani
Enter your ph_no :  1234567890
------------------------------------------------------------
Choose items from the list : 
Shampoo              -        100
Toothpaste           -         50
Detergent            -        150
Dish Soap            -         40
Paper Towels         -         30
Apple                -         60
Hand Soap            -         20
Chocolate            -         70
Soda                 -         50
Chips                -         30
Butter               -         80
Yogurt               -         40
Coffee               -        100
Tea                  -         90
Sugar                -         60
Salt                 -         20
Pepper               -         30
Juice                -         50
Cookies              -         40
Canned Beans         -         30
------------------------------------------------------------
Enter quantity :  5
Enter Product name :  detergent
Do you want to add more items ? (yes/no) :  yes
Enter quantity :  10
Enter Product name :  tea
Do you want to add more items ? (yes/no) :  yes
Enter quantity :  8
Enter Product name :  suger
Please enter the correct spelling!!
Enter Product name :  sugar
Do you want to add more items ? (yes/no) :  yes
Enter quantity :  9
Enter Product name :  canned beans
Do you want to add more items ? (yes/no) :  yes
Enter quantity :  10
Enter Product name :  coffee
Do you want to add more items ? (yes/no) :  no


------------------------------------------------------------
------------------------------------------------------------
                GROCERY STORE XYZ                 
         Date: 22-10-2024  Time: 16:18:47         
 123 Rose street, New Delhi, Phone : 123-456-789  
------------------------------------------------------------
------------------------------------------------------------
Customer name    :     Shivani
Phone no         :     1234567890
----------------------------------------
Detergent         150   x   5.0  
Tea                90   x   10.0 
Sugar              60   x   8.0  
Canned Beans       30   x   9.0  
Coffee            100   x   10.0 
----------------------------------------
Total bill         :  ₹ 3400.0
Discount Applied   :  15.0 %OFF
Final bill         :  ₹ 2890.0
------------------------------------------------------------


         Thankyou for Shopping with us :)         


------------------------------------------------------------
------------------------------------------------------------


Is there a next person in the queue ? (yes/no) :  yes
Enter your name :  Ram
Enter your ph_no :  1234567890
------------------------------------------------------------
Choose items from the list : 
Shampoo              -        100
Toothpaste           -         50
Detergent            -        150
Dish Soap            -         40
Paper Towels         -         30
Apple                -         60
Hand Soap            -         20
Chocolate            -         70
Soda                 -         50
Chips                -         30
Butter               -         80
Yogurt               -         40
Coffee               -        100
Tea                  -         90
Sugar                -         60
Salt                 -         20
Pepper               -         30
Juice                -         50
Cookies              -         40
Canned Beans         -         30
------------------------------------------------------------
Enter quantity :  5
Enter Product name :  cookies
Do you want to add more items ? (yes/no) :  yes
Enter quantity :  10
Enter Product name :  paper towels
Do you want to add more items ? (yes/no) :  yes
Enter quantity :  9
Enter Product name :  butter
Do you want to add more items ? (yes/no) :  no


------------------------------------------------------------
------------------------------------------------------------
                GROCERY STORE XYZ                 
         Date: 22-10-2024  Time: 16:43:04         
 123 Rose street, New Delhi, Phone : 123-456-789  
------------------------------------------------------------
------------------------------------------------------------
Customer name    :     Ram
Phone no         :     1234567890
----------------------------------------
Cookies            40   x   5.0  
Paper Towels       30   x   10.0 
Butter             80   x   9.0  
----------------------------------------
Total bill         :  ₹ 1220.0
Discount Applied   :  15.0 %OFF
Final bill         :  ₹ 1037.0
------------------------------------------------------------


         Thankyou for Shopping with us :)         


------------------------------------------------------------
------------------------------------------------------------


  
