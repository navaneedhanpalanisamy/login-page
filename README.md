## Technologies Used
- *HTML/CSS:* For structuring and styling the login page.
- *JavaScript:* For frontend input validation.
- *Python (Flask):* For backend handling, including password hashing and verification.

## Features
- *Input Validation:* Ensures the username and password meet the required criteria before form submission.
- *Password Hashing:* Secure password storage using werkzeug.security for hashing and verifying passwords.

## How to Run

1. *Frontend:*
   - Open index.html in your browser to view the login page.
   - The form validates the inputs before allowing submission.

2. *Backend (Flask Application):*
   - Install Flask: pip install flask
   - Run the Flask app: python app.py
   - Access the application at https://127.0.0.1:5000/login.

## Input Validation
- *Username:* Must be at least 5 characters long.
- *Password:* Must be at least 8 characters long.

## Password Hashing
The password is hashed using Flask's werkzeug.security package, ensuring secure password storage.
