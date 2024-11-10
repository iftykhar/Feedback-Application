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
MIT License

Copyright (c) 2024 Iftykhar alam

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
 the MIT License. See the LICENSE file for details.

## Acknowledgments
Inspired by simple feedback applications and educational PHP projects.
Developed as part of an exercise to understand file-based storage and PHP basics.