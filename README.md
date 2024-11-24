# Personal Expense Tracker

## Introduction
A Python-based project to manage and analyze personal expenses. Features include adding expenses, viewing them in a table, and analyzing them through visualizations like pie charts.

## Features
- Add and categorize expenses (e.g., Food, Transport).
- View all expenses in a tabular format.
- Analyze spending trends using pie charts.

## Technologies Used
Python: Core programming language.
Pandas: For data manipulation and storage.
Matplotlib: For creating visualizations (pie charts).
CSV: File format used for data storage.
Streamlit (Optional): To convert the project into a web-based application.

## How It Works
1. Add an Expense
The user provides the following:
Date: The date of the expense in YYYY-MM-DD format.
Category: The category of the expense (e.g., Food, Transport, Shopping).
Amount: The amount spent.
2. View All Expenses
The app retrieves and displays all previously saved expenses in a neat table.
3. Analyze Spending
A pie chart shows the proportion of spending in different categories, helping users identify spending trends.

## Project Use Cases
Personal Finance Management: Helps individuals track their daily or monthly expenses.
Budgeting: Assists in understanding spending habits to create and stick to a budget.
Data Analysis Learning Tool: A practical project for beginners to learn Python, Pandas, and Matplotlib.



bash
Copy code
streamlit run expense_tracker.py



