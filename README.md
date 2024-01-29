# Library Management System

This is a simple Library Management System implemented in PHP. It allows users to manage books, students, and transactions such as borrowing and returning books.

## Features

- **Dashboard**: Provides an overview of total books, total students, books borrowed today, and books returned today.
- **Monthly Transaction Report**: Displays a bar chart showing monthly transactions, including borrow and return activities.
- **Transaction Page**: Allows students to view their transaction history, including borrowed and returned books.
- **Book List Page**: Displays a list of books with options to filter by category and search by ISBN, title, or author.
- **Student List Page**: Lists all students with options to add, edit, and delete student records.

## Files and Structure

- **home.php**: Dashboard page displaying various statistics and the monthly transaction chart.
- **transaction.php**: Transaction history page for students, showing borrowed and returned books.
- **index.php**: Main page for browsing and searching books with filtering by category.
- **login.php**: Handles student login, setting session variables upon successful login.
- **student.php**: Page for managing the list of students, including adding, editing, and deleting records.

## Usage

1. **Dashboard**: Access the dashboard by visiting `home.php`. It provides an overview of the library's current status.

2. **Book List**: Browse and search for books on the `index.php` page. Filter books by category and search by ISBN, title, or author.

3. **Student Transactions**: Students can view their transaction history on the `transaction.php` page. They can switch between borrowed and returned books.

4. **Student Management**: Admins can manage the list of students on the `student.php` page. They can add, edit, and delete student records.

## Setup and Configuration

1. **Database Setup**: Configure your database connection in the `includes/session.php` file.

2. **Table Initialization**: Run the SQL script provided in the `database.sql` file to create the necessary tables.

3. **Web Server**: Deploy the application on a web server supporting PHP. You can use tools like XAMPP or WAMP for local development.

4. **Access**: Open the application in your web browser and start using the Library Management System.




