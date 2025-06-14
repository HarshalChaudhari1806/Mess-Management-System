# 🍽️ Mess Management System

This is a PHP-based web application designed to streamline the operations of a mess or cafeteria. The system manages users, orders, menu items, tables, and categories efficiently.

## 📁 Project Structure

Mess Management System/
│
├── class/ # PHP classes for backend logic
├── config/ # Configuration files (e.g., database connection)
├── css/ # Stylesheets
├── database/ # SQL scripts or database setup files
├── inc/ # Includes for modular PHP code (headers, footers, etc.)
├── js/ # JavaScript files
│
├── category_action.php # Backend logic for managing categories
├── category.php # Frontend interface for categories
├── index.php # Entry point/dashboard of the system
├── items_action.php # Backend logic for managing items
├── items.php # Item listing and operations
├── logout.php # Logout functionality
├── order_action.php # Backend logic for handling orders
├── order.php # Frontend for placing and viewing orders
├── table_action.php # Backend for managing tables
├── tables.php # Table listing interface
├── tax_action.php # Backend for managing tax details
├── tax.php # Frontend for tax management
├── top_menus.php # Handles top menu configuration
└── users.php # User management interface

## 🎯 Features

- Add/Edit/Delete **categories**, **items**, **orders**, **users**, **tables**, and **tax** settings.
- Separate PHP scripts for action handlers and frontend interfaces.
- Modular and maintainable structure using separate folders for CSS, JS, classes, and configuration.

## 🛠 Technologies Used

- **Backend**: PHP
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MySQL (assumed from folder structure)
- **Web Server**: Apache (recommended)

## 🚀 How to Run

1. Set up a local web server using XAMPP/WAMP/LAMP.
2. Clone or download this project into the `htdocs` directory (for XAMPP).
3. Create a database and import any `.sql` file provided under `/database/` (if available).
4. Update the DB credentials in the `config/` folder (likely `db.php` or similar).
5. Access the app via `http://localhost/Mess Management System`.

## 📄 License

This project is for educational and non-commercial use.
"""#
