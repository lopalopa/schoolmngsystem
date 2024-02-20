# School Management System

A comprehensive web-based school management system developed in PHP.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Student management (registration, enrollment, attendance)
- Teacher management (profile, assignment management)
- Course management (creation, scheduling, grading)
- Parent portal (view student progress, attendance)
- Administrative tools (user management, reporting, settings)

## Installation

### Requirements
- PHP 7.0+
- MySQL/MariaDB
- Web server (e.g., Apache, Nginx)

### Steps
1. Clone the repository:

2. Navigate to the project directory:

3. Import the database schema:

4. Configure the database connection in `config.php`:
```php
define('DB_HOST', 'localhost');
define('DB_USERNAME', 'root');
define('DB_PASSWORD', '');
define('DB_NAME', 'smsa');

Start your web server and navigate to the project URL in your browser.
