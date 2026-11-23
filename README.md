# SMartBudgetManagger
A project for managing Budget.
# SmartBudget Manager

An Excel workbook that helps you track your monthly income and expenses, see your balance automatically, and get a warning when you spend more than your budget.

**File:** `SmartBudget_Manager.xlsx` | **Version:** 1.0 | **Author:** Benkaddour Farah, Group 03

## What it does

- Records income and expenses
- Sorts expenses into categories (Food, Transport, Rent, Health, Education)
- Calculates your monthly balance automatically
- Shows a pie chart of expenses by category
- Shows **OVER BUDGET** (red) or **WITHIN BUDGET** (green)

## What you need

- Microsoft Excel 2016, 2019, 2021, Microsoft 365, or a compatible spreadsheet program
- No internet connection, add-in or macro
- No formula knowledge: you only type in the data cells

## The three worksheets

| Worksheet | Use it to |
|---|---|
| **Transactions** | Enter income and expenses (rows 4 to 50) |
| **Categories** | See the categories and change each monthly budget |
| **Dashboard** | Read total income, total expenses, balance, budget summary, chart and status |

## Quick start

1. Open `SmartBudget_Manager.xlsx`. If a yellow bar appears, click **Enable Editing**.
2. Go to **Categories** and set your monthly budget for each category (column C).
3. Go to **Transactions**. In the first empty row, enter the date, a description, the **Type** (Income or Expense) and, for an expense, the **Category**.
4. Type the amount in the **Income** column for income, or in the **Expense** column for an expense. Press **Enter**.
5. Open **Dashboard** to see your balance, the chart and the budget status.
6. Save with **Ctrl + S**.

## Good to know

- Do not type in the **Month** column or in the Dashboard: they are calculated automatically.
- Put the amount in the column that matches the Type, or the totals will be wrong.
- Only rows 4 to 50 are counted (47 transactions). Rows below are ignored.
- In some language versions of Excel (for example French) the **Month** column shows "yyyy-09". This does not affect your totals.
- The Dashboard adds up every row, so use one file (or clear old rows) for each month.
- The warning compares **total** expenses with the **overall** budget. Check the "Remaining" column to see a single category going over.
- The five categories cannot be extended in practice: a new category would not appear in the Dashboard.

## Help

See `SmartBudget_User_Guide_Benkaddour_Farah_Group03` for step-by-step instructions with screenshots.
Support: [support e-mail to be added]
