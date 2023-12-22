## Flask-MySQL Application

### Introduction

This is a Flask web application with MySQL database integration. The application is designed for managing student information, attendance, and related triggers.

### Features

- User authentication and authorization.
- CRUD operations for student details.
- Department management.
- Attendance tracking.
- Trigger log recording.

### Technologies Used

- **Flask:** A web framework for Python.
- **MySQL:** A relational database management system.
- **Flask-SQLAlchemy:** SQL toolkit for Flask applications.
- **Flask-Login:** User session management.
- **Werkzeug:** Password hashing.

### Prerequisites

Before running the application, ensure you have the following installed:

- Python
- Flask
- MySQL
- Required Python packages (install using `pip install -r requirements.txt`)

### Database Setup


```bash
# Create MySQL database
mysql -u root -e "CREATE DATABASE students;"

# Import SQL file
mysql -u root students < database.sql


