# Vending Machine in Verilog

This project simulates a simple vending machine using Verilog HDL. The machine allows users to select one of four drinks using a 2-bit input code. Based on the selection, the system outputs a unique item code and displays a message for the purchased item.

## 🧃 Available Drinks

| Select Code | Drink          | Item Code |
|-------------|----------------|-----------|
| `2'd0`      | Coke           | `4'd1`    |
| `2'd1`      | Milkshake      | `4'd2`    |
| `2'd2`      | Fruit Juice    | `4'd3`    |
| `2'd3`      | Lemon Juice    | `4'd4`    |

## 🔧 Features

- 2-bit drink selection input
- 4-bit item code output
- Console message display (`$display`) for feedback
- Handles invalid selection and start conditions gracefully

## 💻 Module Overview

### Inputs:
- `start`: Activates the vending machine
- `select`: 2-bit input to choose a drink

### Outputs:
- `item_code`: 4-bit output representing the selected item
