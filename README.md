Expense Tracker
A simple web app to record daily expenses and see how much was spent in total and by category. Built as the Practical Implementation Project of my YuvaIntern Full Stack Developer internship.

Features
Add an expense with a title, amount, category and date
View all expenses in a table
Delete an expense
See the total spent and the total for each category
Data is saved in the browser (localStorage), so it stays after refreshing
Input validation: the title cannot be empty and the amount must be greater than 0
Technologies Used
HTML for the page structure
CSS for styling
JavaScript for the logic
localStorage for saving data
Project Structure
File	Purpose
Expense.html	Page structure: form, totals and table
style.css	Layout, colors and styling
script.js	Add and delete logic, validation, totals and saving
How to Run
Download or clone this repository.
Open the week3-expense-tracker folder.
Double-click Expense.html to open it in a browser (Chrome or Edge).
How It Works
The form collects the expense details.
addExpense() validates the input and adds the expense to an array.
saveData() stores the array in localStorage.
render() redraws the table and the totals from the array.
deleteExpense() removes an item by its id and refreshes the page data.
Testing
Tested with an empty title, a zero amount, a negative amount, multiple expenses in different categories, deleting an expense, and refreshing the page.

Author
