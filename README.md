GDB links:-

Calculator :- https://onlinegdb.com/26VJytxNb

# 🧮 C Calculator Program

A simple menu-driven calculator in C that performs basic arithmetic operations in a loop until the user chooses to exit.

---

## 📁 Files

| File | Description |
|------|-------------|
| `calculator.c` | Source code for the menu-driven calculator |
| `calculator.exe` | Pre-compiled executable (Windows) |

---

## 📌 Program Details

### `calculator.c` — Menu-Driven Calculator

Repeatedly displays a menu of operations and performs the selected calculation until the user exits.

**Supported Operations:**

| Choice | Operation |
|--------|-----------|
| `1` | Addition (`+`) |
| `2` | Subtraction (`-`) |
| `3` | Multiplication (`*`) |
| `4` | Division (`/`) |
| `5` | Modulus (`%`) |
| `0` | Exit |

**How it works:**
- Uses a `do-while` loop to keep showing the menu until `0` is entered
- Takes two `float` inputs for operations 1–5
- Handles **division by zero** with a proper error message
- Uses `(int)` casting for the modulus operation
- Prints results with `%.0f` for whole numbers and `%.2f` for division

---

## 💻 Sample Run

```
Press 1 for +
Press 2 for -
Press 3 for *
Press 4 for /
Press 5 for %
Press 0 for exit

Enter your choice: 1
Enter the first number: 10
Enter the second number: 5
Addition of 10 and 5 is 15

Enter your choice: 4
Enter the first number: 9
Enter the second number: 0
Division by zero is not possible

Enter your choice: 0
Program exited successfully
```

---


## 🧠 Concepts Used

- `do-while` loop for menu repetition
- `switch-case` for operation selection
- `float` input with `scanf()`
- Division by zero error handling
- Type casting with `(int)` for modulus
