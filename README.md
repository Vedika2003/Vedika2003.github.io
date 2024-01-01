# Vedika2003.github.io

This is a simple Flask web application for user login, registration, and logout using MySQL as the database. It uses the Flask-MySQLdb extension for database connectivity.

Project Structure
plaintext
Copy code
|-- static
|   |-- style.css
|-- templates
|   |-- index.html
|   |-- home.html
|   |-- register.html
|-- main.py
|-- README.md
Pages
Login Page (index.html):

URL: http://localhost:5000/pythonlogin/
Users can log in with their username and password.
Home Page (home.html):

URL: http://localhost:5000/pythonlogin/home
Accessible only if the user is logged in.
Displays a welcome message with the username.
Registration Page (register.html):

URL: http://localhost:5000/pythonlogin/register
Users can register with a unique username, password, and email.
Logout
URL: http://localhost:5000/pythonlogin/logout
Logs the user out and redirects to the login page.
Notes
The application uses Flask-MySQLdb for database connectivity.
Passwords are hashed using SHA-1 with a secret key.
Registration form includes basic validation checks.
The application redirects to the login page by default at http://localhost:5000/.
