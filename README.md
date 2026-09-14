# Clothing Order Management System

A Python-based console application to manage clothing inventory and customer orders.

## Features
- **Inventory Management**: Add, update, delete, view, and search products.
- **Order Management**: Place orders with automatic stock deduction and total cost calculation. View order history.
- **Data Persistence**: Uses CSV files (`inventory.csv` and `orders.csv`) to save data across sessions.

## Requirements
- Python 3.x

## How to Run
1. Open a terminal or command prompt.
2. Navigate to the project directory:
   ```bash
   cd "clothing order management system"
   ```
3. Run the main script:
   ```bash
   python main.py
   ```
4. Follow the interactive console menu to use the system.

## Files
- `main.py`: Interactive CLI and application entry point.
- `models.py`: Core logic including `Product`, `Order`, and `InventoryManager` classes.
- `inventory.csv`: Database file for clothing stock. Added with 5 sample products.
- `orders.csv`: Database file for order history. Added with column headers.
