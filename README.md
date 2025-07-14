# Shopping Cart Console Application
A terminal-based C++ application that simulates an interactive shopping cart system.
This was developed as a final project for the CS1342 course at Southern Methodist University.

---

## Features

- Add items to a virtual cart with:
  - Name
  - Description
  - Price
  - Quantity
- Remove items from the cart by name
- Modify the quantity of existing items
- View descriptions of all items in the cart
- View a full receipt with individual and total costs
- Menu-based user interface via console

---

## Technologies Used

- **Language**: C++
- **I/O**: Standard C++ streams (`cin`, `cout`)
- **Data Structures**: `std::vector`, custom classes

---

## File Overview

| File              | Description |
|------------------|-------------|
| `main.cpp`        | Contains the `main()` function, input/output logic, and menu handler |
| `ItemToPurchase.h/.cpp` | Defines the `ItemToPurchase` class, which represents individual items |
| `ShoppingCart.h/.cpp` | Implements the `ShoppingCart` class, handling all cart operations |

---

## Getting Started

### Requirements

- A C++ compiler (e.g. `g++`, `clang++`)
- Terminal/Command Prompt

### Compilation

```bash
g++ main.cpp ItemToPurchase.cpp ShoppingCart.cpp -o shopping_cart
```
