# Library-management-system
Overview
The Library Management Tool is a Python-based application designed to streamline library operations such as managing book records. It uses a MySQL database backend and provides a user-friendly interface using Gradio for easy interaction.

Technologies Used
Python: Core programming logic
MySQL: Database management
Gradio: Web-based GUI for user interaction
MySQL Connector Pooling: For efficient database connection management

Key Features
Database Connection Pooling: Efficient management of database connections using MySQL connection pooling.

Add New Book: Functionality to add new books to the library, ensuring required details are filled.

Book Search and Status Check (inferred from common LMS functions): Allows users to search for books and check their availability.

Issue and Return Books (likely present in the full script): Handles the borrowing and returning of books.

Simple GUI: Built with Gradio for ease of access and use, even for non-technical users.

Database
The booksdb.sql file is used to set up the librarydata database and necessary tables (likely books, users, transactions, etc.). It is integral to storing and retrieving book and user data.

Security Note
The script currently includes hardcoded database credentials, which is not secure. It’s recommended to use environment variables or a secure configuration file.

Potential Improvements
Implement user authentication.
Add book categorization and search filters.
Improve error handling and logging.
Include book reservation and overdue management.
