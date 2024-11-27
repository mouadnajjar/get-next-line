# Get Next Line

[![1337 Network](https://img.shields.io/badge/42-Network-007396?logo=42&logoColor=white)](https://42network.org/)

## 📝 About the Project

**Get Next Line** is a project from the 42 Network curriculum, focusing on file handling and dynamic memory allocation in C. The goal of the project is to implement a function, `get_next_line`, that reads a line from a file descriptor, handling any file size efficiently and correctly.

This project emphasizes:
- Dynamic memory management.
- Handling edge cases in file reading.
- Understanding and manipulating file descriptors.

---

## 🚀 Features

- Reads one line at a time from a file descriptor.
- Handles multiple file descriptors simultaneously.
- Includes a customizable buffer size for optimized performance.

---

## 🛠️ Functions and Files

### Mandatory

- **`get_next_line.c`**  
  Contains the main logic to read and return a single line from a file descriptor.

- **`get_next_line_utils.c`**  
  Utility functions used by `get_next_line` (e.g., string manipulation, memory management).

- **`get_next_line.h`**  
  Header file defining necessary macros, function prototypes, and includes.

### Bonus

- **`get_next_line_bonus.c`**
- - **`get_next_line_utils_bonus.c`**
  - - **`get_next_line_bonus.h`**   
- Support for multiple file descriptors.
- Optimized performance with different buffer sizes.

---

## 🖥️ Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/mouadnajjar/get-next-line.git
   cd get-next-line
