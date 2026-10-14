# EvenSplit: Group Expense Settlement Optimiser

**Problem ID:** CP007

## 👥 Team Members

1. **Name:** Barun Kumar Gupta | **USN:** 1AT24CS040
2. **Name:** Abhay Sharma | **USN:** 1AT24CS004

## 📌 Problem Overview

EvenSplit is a group expense settlement optimiser designed to simplify the process of splitting expenses among friends, roommates, classmates, and other groups.

When multiple people share expenses, it can become difficult to track who paid how much, who owes money, and how to settle all outstanding balances fairly. EvenSplit aims to solve this problem by calculating individual balances and minimising the number of transactions required to settle the group's debts.

## 🎯 Objectives

- Calculate each member's total expenses and contributions.
- Determine who owes money and who should receive money.
- Optimise settlements to reduce the number of transactions.
- Simplify group expense management through a clear and understandable system.
- Improve transparency and accuracy in shared financial calculations.

## ✨ Features Implemented

- **Expense Management:** Record expenses paid by group members.
- **Balance Calculation:** Calculate each member's net balance based on their contributions and share of expenses.
- **Debt Identification:** Identify members who owe money and members who should receive money.
- **Settlement Optimisation:** Generate settlement transactions to minimise the number of payments where possible.
- **Settlement Summary:** Display the suggested payments required to settle outstanding balances.

*Note: Update this section to reflect the features actually implemented in your source code.*

## 🛠️ Technologies Used

- **Programming Language:** C
- **Compiler:** GCC
- **Development Environment:** Visual Studio Code or any C-compatible IDE
- **Version Control:** Git and GitHub

## ⚙️ Prerequisites

Before running the project, ensure that you have:

- GCC compiler installed.
- Git installed (optional, for cloning the repository).
- A terminal or command-line interface.

To verify your GCC installation, run:

```bash
gcc --version
```

## 🚀 How to Run the Program

### Step 1: Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
```

Replace `<YOUR_GITHUB_REPOSITORY_URL>` with your actual GitHub repository URL.

### Step 2: Navigate to the Project Directory

```bash
cd <YOUR_PROJECT_FOLDER>
```

### Step 3: Compile the Program

```bash
gcc main.c -o main
```

### Step 4: Execute the Program

**macOS / Linux:**

```bash
./main
```

**Windows:**

```bash
main.exe
```

If your source file has a different name, replace `main.c` with the appropriate filename.

## 💻 Sample Run

The following example illustrates how group expense settlement can work. Adjust the input and output to match your actual program.

**Input:**

```text
Enter number of group members: 3

Enter member names:
Alice
Bob
Charlie

Enter number of expenses: 3

Alice paid: 1200
Bob paid: 600
Charlie paid: 0
```

**Illustrative Output:**

```text
========== EvenSplit ==========
Group Expense Settlement Optimiser

Total Group Expense: ₹1800.00
Expense Per Person:  ₹600.00

Settlement Transactions:

Alice receives ₹600.00 from Charlie.
Bob receives ₹0.00.
Charlie pays ₹600.00 to Alice.

Settlement Completed!
```

*The sample is illustrative only. Your program's actual input format, output format, and settlement calculations may differ.*

## 🧠 Working Principle

EvenSplit follows these general steps:

1. **Collect Expenses:** Record the expenses paid by each group member.
2. **Calculate Total Expenses:** Add all contributions to determine the total group expenditure.
3. **Calculate Individual Shares:** Divide the total expenditure according to the selected expense-sharing rule.
4. **Calculate Net Balances:** Subtract each member's fair share from their contribution.
5. **Optimise Settlements:** Match members with negative balances to members with positive balances.
6. **Display Transactions:** Show the suggested payments needed to settle the outstanding debts.

## 📂 Project Structure

```text
EvenSplit/
├── main.c
├── README.md
└── .gitignore
```

The structure may vary depending on the files included in the final implementation.

## 🔮 Future Enhancements

- Support unequal expense sharing.
- Add expense categories and transaction history.
- Allow users to add and remove group members.
- Implement persistent storage for expenses.
- Develop a graphical user interface or web application.
- Generate downloadable settlement reports.
- Support multiple groups and currencies.

## 🎓 Academic Information

**Project:** Capstone Project  
**Problem ID:** CP001  
**Project Title:** EvenSplit: Group Expense Settlement Optimiser  
**Department:** Computer Science and Engineering  
**Institution:** Atria Institute of Technology, Bengaluru

## 📜 License

This project is developed for academic and educational purposes. Licensing terms can be added according to the team's requirements.

---

**EvenSplit — Split fairly. Settle smartly.**