# 🧾 Inventory Management System (GUI) – Python Tkinter

### 📌 Problem Statement

In small businesses or personal setups, tracking stock items manually becomes inefficient and error-prone. This project aims to build a simple, user-friendly inventory management tool with a graphical interface that allows non-technical users to manage stock efficiently.

### 💡 Project Overview
This is a desktop-based Inventory Management System built using Python's **Tkinter** GUI library. It enables users to:
- Add
- Update
- Delete
- Search
- Export inventory items

All inventory items are displayed in a **live-updating table**, and data can be exported to a `.csv` file for backup or further analysis.
### ✨ Key Features

- ✅ **Add Items**: Add new stock items with name, quantity, and price
- 🔁 **Update Items**: Modify existing item quantity or price
- 🔍 **Search Items**: Search and autofill item details into form fields
- ❌ **Delete Items**: Remove unwanted items from the inventory
- 💾 **Export to CSV**: Export the current inventory to `inventory_export.csv`
- 📊 **Live Table View**: Instantly updates table after each action
- 🛡 **Form Validation**: Prevents invalid inputs using real-time checks and pop-ups

### 🛠 Technologies Used
| Python 3     :   Core programming language      
| Tkinter      :   GUI development                
| csv module   :   Exporting inventory data       
| tk.Treeview  :   Displaying data in tabular GUI 

### 🧠 Logic & Functionality
* All inventory data is stored temporarily in a Python dictionary (inventory = {}), where 
each key is an item name and the value is a dictionary containing quantity and price. 
* Form inputs are validated before any action is performed (e.g., checking if price is a 
number, quantity is an integer, and all fields are filled). 
* GUI components like Entry, Label, and Button are used to interact with the user. 
* A Treeview widget is used to render a live table view that refreshes after every 
inventory operation. 
* The "Export CSV" button writes all inventory data to a inventory_export.csv file. 
### What I Learned: 
* How to build a real-world GUI using Tkinter 
* Data structure handling using dictionaries 
* Input validation and user interaction with pop-up messages 
* How to use Treeview for dynamic table rendering 
* File operations for exporting data (csv.writer) 
* GUI application design patterns and event-driven programming
