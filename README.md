# 📦 Inventory Sales Processor (Python)

A simple Python program to manage sales, update inventory quantities, and detect items that are out of stock.  
This script demonstrates tuple-based inventory processing using functions and user input.

---

## 🚀 Features

### ✔ Process Sales
- Takes **SKU** and **quantity sold**
- Decreases stock if available
- Prevents sales if:
  - SKU does not exist  
  - Stock is insufficient  

### ✔ Identify Zero Stock Items
- Scans inventory and lists all SKUs with **zero remaining quantity**

### ✔ Menu-Driven Execution
- User can input SKU and sold quantity repeatedly  
- Enter `'q'` at any time to exit the program

---

## 🧾 Inventory Structure

The inventory is stored as a list of tuples:

```python
[(SKU, quantity), ...]
