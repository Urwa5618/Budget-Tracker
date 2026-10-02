# 💰 Monthly Expense Tracker

A console-based **Monthly Expense Tracker** developed in **C** to help users manage their monthly income and track expenses across different categories.

The program allows users to record daily expenses, monitor their remaining balance, receive spending warnings, and view detailed daily, weekly, and monthly expense reports.

---

## ✨ Features

* 💵 Enter and manage monthly income
* 📅 Support for **28–31 day months**
* 📊 Track expenses day-by-day
* 🗂️ Categorize expenses into:

  * 🍔 Food
  * 🚗 Transport
  * 💡 Utilities
  * 🏥 Health
  * 🎮 Entertainment
  * 📦 Other
* ⚠️ Prevent expenses from exceeding the available monthly income
* 🔔 Spending warnings at:

  * 50% of income
  * 75% of income
  * 90% of income
* 📈 Generate weekly expense reports
* 📋 Display complete monthly expense summaries
* 🔎 Check expenses for a specific day
* 💰 Calculate remaining balance automatically
* ✅ Input validation for invalid values and choices
* 🧾 Monthly utility bill tracking

---

## 🛠️ Technologies Used

* **Language:** C
* **Concepts:** Functions, Arrays, 2D Arrays, Loops, Conditional Statements, Input Validation
* **Data Handling:** Static Arrays
* **Interface:** Console / Terminal

---

## 🧠 Programming Concepts

This project demonstrates several fundamental C programming concepts:

* Functions and function prototypes
* Two-dimensional arrays
* Character arrays and strings
* Modular programming
* `for`, `while`, and `do-while` loops
* Conditional statements
* Input validation using `scanf()`
* Passing parameters to functions
* Basic data aggregation and calculations
* Menu-driven console interaction

---

## 📊 Expense Tracking

Expenses are stored using a two-dimensional array:

```c
float dailyExpenses[MAX_DAYS][CATEGORIES];
```

Each row represents a **day**, while each column represents an **expense category**.

This allows the program to efficiently maintain and calculate daily, weekly, and monthly spending.

---

## ⚠️ Income Protection

The tracker prevents users from recording expenses that exceed their monthly income.

For example:

```text
Error: Expense exceeds your monthly income!
Remaining Balance: 2500.00
```

This ensures that the recorded expenses remain within the user's available budget.

---

## 📅 Reports

The program provides multiple ways to analyze expenses:

### Daily Report

View the expenses recorded for a specific day.

### Weekly Report

After every seven days, the user can generate a weekly report showing category-wise spending and the weekly total.

### Monthly Summary

View category-wise expenses across the entire month along with:

* Total Monthly Expenses
* Remaining Balance

### Full Month Table

Displays every day of the month with its weekday, category-wise expenses, and daily total.

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/budget-tracker.git
```

### 2. Open the Project

Open the `.c` file in any C-supported IDE or compiler such as:

* Code::Blocks
* Dev-C++
* Visual Studio
* VS Code with a C compiler
* GCC

### 3. Compile

Using GCC:

```bash
gcc budget_tracker.c -o budget_tracker
```

### 4. Run

```bash
./budget_tracker
```

---

## 🖥️ Sample Workflow

```text
=== Monthly Expense Tracker ===

Enter number of days in the month (28–31): 30
Enter your monthly income: 50000
Enter Utilities bill for the month: 5000

Day 1 - Monday
Was there any expense today? (1=Yes, 0=No): 1

Select category:
1. Food
2. Transport
4. Health
5. Entertainment
6. Other

Enter category number: 1
Enter amount: 1200
```

The user can continue entering expenses and later choose which reports they want to view.

---

## 🎯 Project Objective

The main objective of this project is to provide a simple console-based solution for **personal expense management** while demonstrating practical implementation of fundamental C programming concepts.

---

## 🔮 Future Improvements

Possible future versions could include:

* 💾 File handling for saving expenses permanently
* 📅 Custom expense dates
* 📊 Graphical expense charts
* 🔐 User accounts and login system
* 🔎 Expense search and filtering
* ✏️ Edit and delete existing expenses
* 📈 Monthly spending trends
* 💻 GUI-based version

---

## 👨‍💻 Authors

**Urwa Rafique and Ali Asghar**

Computer Science Undergraduate
FAST-NUCES Karachi

---

⭐ If you find this project useful, consider giving the repository a star!
