# Feedback Application

This is a PHP-based web application that allows users to submit feedback. The application supports user authentication and provides a dashboard where users can view and manage their submitted feedback.

## Features

- User Registration and Login
- Feedback Submission
- Dashboard to View Submitted Feedback
- File-based Storage System

## Project Structure

- `index.php`: The entry point of the application.
- `login.php` / `register.php`: User authentication pages.
- `dashboard.php`: User dashboard to view feedback.
- `feedback.php`: Page for submitting feedback.
- `FeedbackClass.php`: Core class handling feedback operations.
- `UserAuth.php`: Authentication logic for user login and registration.
- `feedback/`: Folder storing feedback data files.
- `file/`: Folder storing user-specific files.
- `images/`: Image assets used in the application.

## Prerequisites

- PHP (version 7.4 or above recommended)
- A web server (such as Apache or Nginx)

## Installation

### 1. Clone the repository:
     git clone https://github.com/yourusername/Feedback-Application.git
### 2. Move into the project directory:
     cd Feedback-Application

## Start a local PHP server:
    php -S localhost:8000
Access the application by visiting http://localhost:8000 in your web browser.

## Usage
    Register as a new user by providing an email and password.
    Log in using the registered credentials.
    Submit feedback through the feedback form on the dashboard.
    View a list of submitted feedback items on your dashboard.
## File Storage
User data and feedback are stored as .txt files in file/ and feedback/ directories.
This approach allows for easy data management without a database.
## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Inspired by simple feedback applications and educational PHP projects.
Developed as part of an exercise to understand file-based storage and PHP basics.