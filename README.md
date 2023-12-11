# ReadUp

This is a simple Library Management System implemented using Flask and MySQL.

## Features

- **User Authentication:** Users can sign up, log in, and log out to access the system.
- **Explore Books:** Browse and explore a collection of books with pagination support.
- **Bookmark Books:** Logged-in users can bookmark their favorite books.
- **My List:** View and manage the list of bookmarked books.
- **Search:** Search for books based on titles or authors.
- **Book Details:** View detailed information about a specific book.

## Getting Started

### Prerequisites

- Python 3
- MySQL

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/library-management.git
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Set up the MySQL database. Create a database and update the configuration in config.py:
    ```bash
        HOST = "your_mysql_host"
        USER = "your_mysql_username"
        PASSWORD = "your_mysql_password"
        DATABASE_NAME = "your_mysql_database"
        PORT = your_mysql_port
    ```
4. Run the [create_tables.sql](./mysql_tables/create_tables.sql) file to create the tables in MySQL
5. Run the [insert_tables.ipynb](./mysql_tables/insert_tables.ipynb) file to insert into the tables
6. Run the application using the command
   ```bash
    python app.py
   ```
7. Open your web browser and go to http://localhost:5000.

## Usage
- Create an account or log in to access the features.
- Explore books, bookmark your favorites, and manage your list.

> Thank you
