# Bank-Management-System

A console-based bank account management system written in C++. It lets you create and manage customer accounts from a text menu, with records saved to a binary file so data persists between runs.

## Features

| Option | Action |
|--------|--------|
| 1 | Create a new account |
| 2 | Deposit money |
| 3 | Withdraw money |
| 4 | Balance enquiry |
| 5 | List all account holders |
| 6 | Close an account |
| 7 | Update an account (name, type, balance) |
| 8 | Exit |

- Accounts have a number, holder name, type (savings or current) and balance.
- Data is stored in `Bank_Account.dat`, created in the working directory on first use.
- Built around a `Bank_Account` class using C++ file streams (`fstream`).

## Build and run

```bash
g++ main.cpp -o bank
./bank
```

The program clears the screen with `system("CLS")`, so it is written for Windows. On Linux or macOS, replace `CLS` with `clear`.

## Files

| File | Description |
|------|-------------|
| `main.cpp` | Account class, file handling and menu |

## Ideas for improvement

- Input validation and PIN protection
- Cross-platform screen clearing
- Transaction history


---

<sub>Made by [tanaytejush](https://github.com/tanaytejush)</sub>
