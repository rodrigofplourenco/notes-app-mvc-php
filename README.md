# Notes App (Almost a mikro MVC framework as I named it)
This was a simple project intended for learning raw PHP programming applying MVC design pattern, also made use of Pest package for testing (very simple testing, only for learning too). Maybe I should create a better framework version of it in the near future.

## Features
- Routing system with middlewares and errors support
- Form validator
- Service container coupled within App
- Simple functions.php with helper functions like dd for debugging
- Custom exceptions for automatic redirection
- Authentication system
- Session system with flashing data support
- Automatic lookup for directories
- CRUD system for notes and also a simple full auth system
- Much more, feel free to checkout everything

## How to Setup
Just clone this repository, import the database from database.sql, configure on config.php (optionally see Core/Database.php for the implementation), run composer install and just start the project (php -S localhost:8888 -t public) and it should start the server on port 8888.
