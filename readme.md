# Center for Comparative Archaeology - Database Management System

## Overview
The **Center for Comparative Archaeology** website is a platform designed to simplify access to, contribution to, and administration of archaeological databases. This user-friendly system facilitates downloading existing datasets and enables users to actively contribute to their expansion. The project aims to create a hub for managing, contributing to, and disseminating archaeological databases.

This system is built using **Python Flask**, **MySQL**, **SQLAlchemy**, **HTML**, and **CSS**, allowing users to view, download, contribute to datasets, and request new project creation upon registration and login.

## Features

- **Guest Access:**
  - View and download archaeological datasets in Excel and CSV formats.

- **Registered User Access:**
  - Submit requests to create new projects.
  - Contribute to existing projects by uploading Excel sheets matching the existing dataset's structure.
  - Access profile pages to display previous projects and research interests.

- **Moderator Dashboard:**
  - Review and approve requests from registered users (for creating new projects or contributing to existing ones).

## Dependencies

Ensure the following dependencies are installed in a virtual environment:

- Flask
- Flask-WTF
- Flask-SQLAlchemy
- Pandas
- MySQL Connector for Python
- Phonenumbers
- Flask-Login
- WTForms-Alchemy

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo.git
    ```

2. Navigate to the project directory:
    ```bash
    cd your-repo
    ```

3. Create a virtual environment:
    ```bash
    python3 -m venv dbenv
    ```

4. Activate the virtual environment:

    - On macOS/Linux:
        ```bash
        source dbenv/bin/activate
        ```
    - On Windows:
        ```bash
        dbenv\Scripts\activate
        ```

5. Install the required dependencies:
    ```bash
    pip install Flask Flask-WTF Flask-SQLAlchemy pandas mysql-connector-python phonenumbers Flask-Login wtforms-alchemy
    ```

6. Set the Flask environment variables:
    ```bash
    export FLASK_ENV=development
    export FLASK_APP=script.py
    ```

## Usage

1. Run the application:
    ```bash
    flask run
    ```

2. Access the application in your browser:
    ```bash
    http://127.0.0.1:5000
    ```

## System Requirements

### 1. Web Server:
- Flask web framework for Python with **Werkzeug** as the WSGI server.
- Deployable on a web server supporting Flask applications (e.g., **Gunicorn**, **uWSGI**).
- Optional reverse proxy setup with **Nginx** or **Apache** for enhanced security and performance.

### 2. Database Management System:
- **MySQL 8.0** for data storage and retrieval.
- **Flask-SQLAlchemy** for database interactions.
- Efficient database schema design for user profiles, notifications, contributions, and moderation logs.

### 3. Programming Languages:
- **Python 3.7+** for server-side scripting.
- **HTML5, CSS3, JavaScript** for front-end development.
- **Jinja2** templating engine for integrating Python with HTML.

### 4. User Authentication and Security:
- **Flask-Security** for authentication and authorization.
- Secure password hashing using **Werkzeug**.
- Input validation and protection against common web vulnerabilities.

### 5. User Interface Compatibility:
- Responsive design using **HTML5** and **CSS3**.
- **JavaScript** for dynamic content and interactivity.

### 6. Notification System:
- Real-time updates using **Flask-SocketIO** for WebSocket functionality.
- Email notifications using **Flask-Mail** or similar extensions.

### 7. User Management:
- **Flask-Login** for session management.
- User registration and profile management through Flask forms.
- Account deletion functionality with data retention policies.

### 8. Moderation Tools:
- **Flask-Admin** or custom interfaces for moderation.
- Moderator activity logging.

### 9. File Management:
- Secure file uploads via **Flask-Uploads**.
- File type verification for uploaded content.

### 10. Compatibility Testing:
- Cross-browser compatibility testing (Chrome, Firefox, Safari).
- Testing for responsive design across devices and resolutions.

### 11. Documentation and Help System:
- Comprehensive documentation for developers on setup, configuration, and maintenance.
- In-app help system or a separate knowledge base for users.

### 12. Backup and Recovery:
- Automated backups of the MySQL database using tools like **mysqldump**.
- Disaster recovery plan for minimal data loss and downtime.

## Contributors
- **Aishwarya Bhargava**
- **Anusha Shivakumar**
- **Bhavana Devulapally**
- **Shusrita Venugopal**
