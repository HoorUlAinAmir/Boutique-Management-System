# Boutique Management System

A C++ console-based Boutique Management System that manages boutique operations such as customer management, employee management, product handling (e.g., children's clothing), and cashier functionalities. This project is designed for educational purposes and demonstrates object-oriented programming, file handling using JSON, and modular design.

## 📁 Project Structure


## ⚙️ Features

- Add, update, and delete customer records
- Manage employee data
- Handle boutique product inventory
- Simple cashier interface for purchase processing
- JSON file-based data persistence
- Modular object-oriented code structure
- Buildable using both `make` and `CMake`

## 🛠️ Installation & Build

### Prerequisites
- C++17 compatible compiler (e.g., `g++`)
- `make` or `cmake`
- JSON for Modern C++ library (integrated if `nlohmann/json` used)

### Build using Makefile
```bash
make
./boutique

mkdir build
cd build
cmake ..
make
./boutique
make test
# or run the test executable directly
./test_boutique
