# inventory-management-system

# Inventory Management System

This project implements a simple inventory management system for a retail business using Python.

## Classes

### Product

The `Product` class manages the products in the inventory.

### Order

The `Order` class manages the orders placed for products.

## Usage

### Adding a Product

```python
from product import Product

Product.add_product("Laptop", "Electronics", 50, 1000, "Supplier A")
Product.add_product("Phone", "Electronics", 30, 500, "Supplier B")
