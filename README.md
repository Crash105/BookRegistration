# Book Registration System

## Overview
This project implements a book registration system that allows users to add books by category to a database. The system utilizes PHP for data management and phpMyAdmin for database administration.

## Features
- Add books to the database with category classification
- Retrieve and display all books from the database
- User-friendly interface for book management

## Technology Stack
- PHP: Used for server-side scripting to handle data submission and retrieval
- MySQL: Database management system
- phpMyAdmin: Web-based administration tool for MySQL databases

## How It Works
1. Users input book details including title, author, and category through a web form.
2. PHP processes the form submission and inserts the data into the MySQL database.
3. Users can view all books in the database, which are retrieved using PHP and displayed on the webpage.

## Database Structure
The database likely includes a table for books with fields such as:
- ID (auto-incrementing primary key)
- Title
- Author
- Category
- Date Added

## Future Enhancements
- Implement search functionality
- Add user authentication for admin access
- Include book cover image uploads

## Setup Instructions
1. Download and install XAMPP from the official website.
2. Clone or download the project folder from GitHub.
3. Place the downloaded folder in the xampp/htdocs directory.
4. Start XAMPP and turn on Apache and MySQL services.
5. Open a web browser and go to http://localhost. This should show the XAMPP welcome page.
6. Click on phpMyAdmin in the XAMPP dashboard to access the database management interface.
7. In phpMyAdmin, import the bookstore.sql file provided with the project.
8. Open the database.php file in the project and ensure that the bookstorename, username, and password match your phpMyAdmin settings.
s)
