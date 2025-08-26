# Expense-tracker-web-app

# Expense Tracker — Single File App

A lightweight, **local-first expense tracker** built entirely in a single HTML file. Track your **income, expenses, and transactions** without any backend. Data is stored locally in your browser using `localStorage`, making it **privacy-friendly** and easy to use.

---

## Features

- Add, edit, and delete transactions (income & expenses)
- Categorize transactions (Food, Transport, Salary, Health, Entertainment, etc.)
- Track **current balance**, total income, and total expenses
- Filter transactions by:
  - Text search
  - Month
  - Category
- Quick actions:
  - Add sample data
  - Delete all transactions
  - Export as JSON
  - Import JSON
  - Download CSV
- Visual insights with **charts**:
  - Pie chart for spending by category
  - Bar chart for monthly totals (past 6 months)
- Responsive design for desktop and mobile

---

## Demo

Open the `index.html` file in any modern browser. No setup or server required.

---

## Usage

1. **Adding a Transaction**
   - Fill in the **Title**, **Amount**, **Type** (Income/Expense), **Category**, and **Date**.
   - Click **Add Transaction**.

2. **Editing a Transaction**
   - Double-click a transaction or click the **Edit** button.
   - Update details and submit the form.

3. **Deleting a Transaction**
   - Click the **Delete** button or confirm deletion.

4. **Filtering & Searching**
   - Use the search boxes or filters on the right to find transactions by text, month, or category.

5. **Export / Import**
   - **Export JSON**: Save all transactions as a `.json` file.
   - **Import JSON**: Load transactions from a JSON file.

6. **Download CSV**
   - Export all transactions in `.csv` format for spreadsheet use.

---

## Built With

- **HTML5 & CSS3** — Single file structure
- **JavaScript** — CRUD operations, filtering, and charts
- **LocalStorage** — Persistent local storage of user data
- **Canvas API** — Charts for insights

---

## Folder Structure

Since this is a **single-file application**, all code is contained in `index.html`:

