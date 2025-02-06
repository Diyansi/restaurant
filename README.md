# DIYANSI'S Restaurant Billing System

## Description
This program simulates a restaurant billing system where a user can generate invoices, view saved invoices, and search for a specific customer's invoice. It allows for the input of customer details, item names, quantities, and prices, then generates and displays an invoice with discounts, taxes, and totals.

## Features
- **Generate Invoice**: Input customer details and item information to generate an invoice.
- **View All Invoices**: Display all previous invoices stored in a file.
- **Search Invoice**: Search for a specific customer's invoice by name.
- **Save Invoice**: Option to save the generated invoice to a file (`RestaurantBill.dat`).
- **Invoice Footer**: Automatically calculates subtotal, discount, taxes (CGST & SGST), and the grand total.

## Operations
1. **Generate Invoice**: 
   - Enter customer name, items, quantity, and price to generate an invoice.
   - Option to save the invoice to a file.
   
2. **Show All Invoices**: 
   - View all previously generated invoices from the file.

3. **Search Invoice**: 
   - Search and view the invoice by entering the customer's name.

4. **Exit**: Exit the program.

## Example

============DIYANSI'S. RESTAURANT============ Please select your preferred operation:

Generate Invoice
Show all Invoices
Search Invoice
Exit
Your choice: 1

Please enter the name of the customer: John Doe Please enter the number of items: 2

Item 1: Pizza Quantity: 2 Price: 10.50

Item 2: Coke Quantity: 1 Price: 2.00

Invoice Generated Successfully

Do you want to save the invoice [y/n]: y Successfully saved


## File Storage
Invoices are saved in a file named `RestaurantBill.dat` for later viewing or searching.

## Code Overview
The program consists of the following key functions:
- **generateBillHeader**: Displays the header of the invoice with customer name and date.
- **generateBillBody**: Displays each item, quantity, and total price.
- **generateBillFooter**: Calculates and displays the total, discount, CGST, SGST, and grand total.
- **main**: Handles the user interface for choosing operations and interacting with the program.

## Requirements
- C Compiler (GCC or any other standard compiler)

## Author
Created by **Diyansi Chaudhary**
