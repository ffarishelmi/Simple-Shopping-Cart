# Simple Shopping Cart Using Python

## Description
This is a simple example of applying the concept of callback and calling others function in Python. Callback Function is a way in which a function can be passed as a parameter to another function, this makes the code flexible as we can use a function to execute a specific task to run alongside another specific task. Calling Other Functions is a way of calling a function as a statement within a function, the purpose of which is to divide the function into specific tasks and then run it alongside other functions.

These two concepts can make code more modular, manageable, easy to debug and extend by simply managing each specific function separately, or creating a new function and adding it to an existing function as a statement.

This project also implemented other concepts such as creating a separate Python file for each function, and then calling each other function in different files by importing. Then implemented the concept of CRUD (create, read, update, delete), and integration between program files, so the code continues to execute the loop until the stop option is selected.

## Features
There are two ways to log in as:
1. Admin
    - View all item data
    - Adding item data
    - Update item data
    - Deleting item data
2. User
    - View all item
    - View by sorting item
    - View by filtering item
    - Add item to cart
    - View cart
- Switch log in
- Quit program

## Installation
1. Install dependencies:
    ```bash
    pip install tabulate
    ```
2. Clone this repository:
    ```bash
    git clone https://github.com/ffarishelmi/Simple-Shopping-Cart.git
    ```
3. Enter the project directory:
    ```bash
    cd Simple-Shopping-Cart
    ```

## Run Program
You only need to run `main.py` file by typing `python main.py`
