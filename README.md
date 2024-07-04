# Stock Management System

This **Stock Management System** can be accessed by two types of users: **System Admins** and **Staff**. The **Admin User** can access and manage all the pages, forms, and features of the web application, while the **Staff Users** have limited access only.

The Stock Records, such as the Purchase Order, Receiving, etc., in this project have print features for each record. 

## Project Workflow

1. **Populate Important Lists**: Admin users must first populate all the important lists, which are the supplier list and the item list.
2. **Create Purchase Order**: Users will create a Purchase Order Record for a supplier.
3. **Receive Items**: Users can receive the items in each purchase order. A PO Record is required to add stock of the item.
4. **Back Order Record**: When receiving items, if the supplier delivers some items or not complete, the system will automatically create a new Back Order Record for the items that are not delivered yet. BO records work like the Purchase Order Record.
5. **Return Record**: When received items have problems or issues, the management can create the Return Record. Upon saving this file, the system will also automatically deduct the damaged items from the stock availability.
6. **Sales Record**: The sales record is the record of the company for stocks that have been purchased by their clients or customers. Each stock listed in the sales record will also be deducted from the stock availability.

## Features

- Secure Login and Logout
- Manage Supplier List (CRUD)
- Manage Item List (CRUD)
- Manage Purchase Order Records
  - Create New
  - Edit Record
  - View Record
