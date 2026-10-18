# Maintenance Request System

A web-based application for managing maintenance requests and tracking service tickets. This project was developed as part of university coursework in Web Application and Technologies.

## Overview

The system helps customers submit maintenance requests and allows authorized staff and managers to manage and track tickets through a web interface.

## Features

- User authentication and session management.
- Role-based access for customers, staff, and managers.
- Maintenance ticket creation and tracking.
- Ticket status and urgency management.
- Ticket assignment and management.
- Search and filtering capabilities where implemented.
- Image upload for maintenance requests where supported.
- Responsive web interface.

## Technologies

- HTML5
- CSS3
- PHP
- MySQL
- PDO for database access

## Project Structure

- `ass1/` — Initial HTML pages and interface structure.
- `assTwo/` — PHP ticket management functionality.
- `assThree/` — Interface styling and CSS improvements.

Adjust the folder names above to match the actual repository structure.

## Database Setup

1. Install a local PHP and MySQL environment, such as XAMPP.
2. Create the database using the SQL schema provided in the `database/` directory.
3. Configure the database connection in `dbconfig.in.php`.
4. Place the project in the local web server directory.
5. Start the web server and MySQL service.
6. Open the application through your local server.

Do not commit real database passwords or private credentials.

## Security Considerations

- Use prepared statements for database operations.
- Validate user input on the server.
- Restrict access to protected pages based on authentication and user role.
- Validate uploaded files before storing them.
- Keep database credentials outside public source control.


## Learning Outcomes

This project provided practical experience with server-side web development, database integration, session management, role-based access control, and front-end styling.

## Academic Project

Developed as part of the COMP334 Web Application and Technologies coursework at Birzeit University.
