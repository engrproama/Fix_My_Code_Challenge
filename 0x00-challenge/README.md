# Fix_My_Code_Challenge

Welcome to the **Fix My Code Challenge** repository! This project is designed to test and improve your debugging skills by providing you with code that contains bugs. Your mission is to find and fix these issues.

## Project Structure

The project is organized into different challenges, each located in its own file or directory. Below is an overview of the structure:

```plaintext
Fix_My_Code_Challenge/
│
├── 0x00-challenge/
│   ├── 0-fizzbuzz.py
│   ├── 1-print_square.js
│   ├── 2-sort.rb
│   ├── 3-user.py
│   └── 4-delete_dnodeint/
│       ├── add_dnodeint_end.c
│       ├── delete_dnodeint_at_index.c
│       ├── free_dlistint.c
│       ├── lists.h
│       ├── main.c
│       └── print_dlistint.c
└── README.md
```

### 0x00-challenge

This directory contains several files, each with a specific challenge. Your task is to fix the code in these files. The details for each file are as follows:

#### 0-fizzbuzz.py
- **Language:** Python
- **Description:** A simple implementation of the classic FizzBuzz problem. The code prints numbers from 1 to 100, but for multiples of three, it prints "Fizz" instead of the number, and for the multiples of five, it prints "Buzz". For numbers which are multiples of both three and five, it prints "FizzBuzz".

#### 1-print_square.js
- **Language:** JavaScript
- **Description:** This file contains a function that prints a square made of `#` characters. The size of the square is determined by the input parameter.

#### 2-sort.rb
- **Language:** Ruby
- **Description:** This Ruby script is supposed to sort an array of integers. The current implementation might have logical or syntactical errors that need to be addressed.

#### 3-user.py
- **Language:** Python
- **Description:** This script involves a simple user management system. It allows for the creation of users and manipulation of user attributes. The script might have issues related to object-oriented programming concepts or logical errors.

#### 4-delete_dnodeint

This sub-directory contains a series of C files related to managing a doubly linked list. The code might have issues with memory management, pointer handling, or linked list operations.

- **add_dnodeint_end.c:** Adds a new node at the end of a doubly linked list.
- **delete_dnodeint_at_index.c:** Deletes the node at a specified index in a doubly linked list.
- **free_dlistint.c:** Frees the entire doubly linked list.
- **lists.h:** Header file containing the structure definitions and function prototypes.
- **main.c:** The main file to test the linked list functions.
- **print_dlistint.c:** Prints all elements of a doubly linked list.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Fix_My_Code_Challenge.git
   cd Fix_My_Code_Challenge/0x00-challenge
   ```

2. **Fix the Code:**
   - Open each file and identify the bugs or issues.
   - Make the necessary corrections.
   - Test your code to ensure that it works as expected.

3. **Run the Tests:**
   - For Python files: 
     ```bash
     python3 filename.py
     ```
   - For JavaScript files:
     ```bash
     node filename.js
     ```
   - For Ruby files:
     ```bash
     ruby filename.rb
     ```
   - For C files:
     Compile and run the `main.c` file:
     ```bash
     gcc -Wall -Werror -Wextra -pedantic *.c -o dlist
     ./dlist
     ```

4. **Commit Your Changes:**
   - After fixing the code, commit your changes to the repository:
     ```bash
     git add .
     git commit -m "Fixed issues in 0x00-challenge"
     git push origin main
     ```

## Contribution Guidelines

Feel free to fork this repository and create a pull request with your fixes. Contributions are always welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

If you have any questions or need further clarification, feel free to reach out to the repository owner or open an issue.

Happy coding and debugging friends
