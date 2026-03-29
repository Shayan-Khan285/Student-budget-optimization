# Student-budget-optimization
A high-quality `README.md` is the "front door" of your project. It explains to a user (or a potential employer) what your code does, why it exists, and how to run it.

Below is a professional, well-structured README specifically for the Python code you provided.

---

# 🎓 Monthly Student Budget Optimizer

A lightweight Python command-line tool designed to help students track their monthly expenses, visualize spending patterns, and optimize their savings using the **50/30/20 rule**.

## 📌 Project Overview
Managing finances as a student is often a challenge due to limited income and fluctuating costs. This project provides a programmatic solution to track monthly cash flow, categorize spending, and provide actionable financial advice based on your remaining balance.

## 🚀 Key Features
* **Categorized Tracking:** Specifically tracks common student costs like Rent, Groceries, and Academic Supplies.
* **Real-time Optimization:** Automatically categorizes your financial health into *Healthy*, *Warning*, or *Alert* status.
* **Savings Suggestions:** Calculates a 20% savings goal if the budget allows.
* **Percentage Breakdown:** Shows exactly what percentage of your total income is going to each category.
* **Error Handling:** Prevents crashes by validating that inputs are numerical.

## 💻 Installation & Usage

### Prerequisites
* **Python 3.x** installed on your machine.

### Running the Script
1.  **Download** the `budget_optimizer.py` file.
2.  **Open your Terminal** or Command Prompt.
3.  **Navigate** to the folder where the file is saved.
4.  **Run** the following command:
    ```bash
    python budget_optimizer.py
    ```

## 🛠️ How it Works (Logic Flow)
The script follows a simple three-step process:
1.  **Data Input:** The user enters their total monthly allowance and individual expenses.
2.  **Calculation:** The system calculates $Remaining = Income - Total Expenses$.
3.  **Optimization Logic:**
    * **If Remaining < 0:** High-priority alert to reduce discretionary spending.
    * **If Remaining < 10%:** Warning to build a larger emergency buffer.
    * **If Healthy Surplus:** Suggests a **20% savings target** based on total income.

## 📊 Example Output
```text
--- 🎓 Monthly Student Budget Optimizer ---
Enter your total monthly income/allowance: $1200

==============================
Total Expenses: $950.00
Remaining Balance: $250.00
==============================
✅ Healthy Budget! You can save $240.00 (20%) this month.

Expense Breakdown:
- Rent/Dorm: 41.7%
- Groceries: 16.7%
- Social & Fun: 8.3%
...
```

## 📂 Project Structure
* `budget_optimizer.py` — The core Python script containing the logic and CLI.
* `README.md` — Project documentation (this file).

