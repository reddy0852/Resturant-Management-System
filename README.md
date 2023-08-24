# Restaurant Management System

The Restaurant Management System is a web application that enables users to access a comprehensive view of available items in the restaurant. It utilizes HTML, CSS, JavaScript, Bootstrap, PHP, and MySQL to provide a user-friendly experience for both customers and administrators.

## Features

- User login to access the restaurant's item list.
- Frontend design using HTML, CSS, JS, and Bootstrap.
- Backend database powered by MySQL.
- Admin functionality to update the restaurant's item list.

## Technologies

- HTML
- CSS
- Bootstrap
- JavaScript
- MySQL
- Git
- PHP

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/reddy0852/Resturant-Management-System.git
   ```
2. Place the project folder in your XAMPP server's `htdocs` directory.

3. Import the provided SQL database:
    - Open phpMyAdmin by navigating to ` http://localhost/phpmyadmin ` in your browser.
    - Create a new database and name it something like `restaurant_management_system`.
    - Go to the Import tab and select the SQL file (`restaurant_management_system.sql`) provided in the repository's root directory.
    - Click "Go" to import the database structure and sample data.
4. Configure the database connection:
    - Open the `config.php` file located in the `includes` directory.
    - Update the database credentials to match your MySQL configuration.
5. Access the application:
    - Start your XAMPP server and make sure Apache and MySQL are running.
    - Open a web browser and navigate to `http://localhost/Resturant-Management-System`.
Usage
1. As a User:
    - Log in using your credentials.
    - Browse the list of available items.
2. As an Admin:
    - Log in using admin credentials (if provided or configured).
    - Update the item list through the admin interface.