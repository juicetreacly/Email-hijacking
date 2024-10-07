# Email-hijacking
# This for educational purposes only
# Batch Script: Call of Duty Mobile Setup or any other app/exe
This batch script simulates a simple login prompt for installing Call of Duty Mobile. It collects the user's email and password and writes them to a file called Help Selenium.bat. Below is a detailed breakdown of the script's behavior:

# Functionality:
Title & Setup: The batch file starts by setting the console title to CALL OF DUTY MOBILE setup and clears the screen.

User Login Prompt:

It displays a login interface asking the user for their email and password.
The input provided for the email and password is captured by the script and stored in two variables (MAIL and PSWD).
Logging Credentials:

The email and password provided by the user are then written to a file named Help Selenium.bat in the format:

# java💻
Copy code
EMAIL = user@example.com
PASSWORD = user_password
Timeout & Visual Feedback:

The screen is cleared after the user inputs their credentials.
A short timeout of 3 seconds (TIMEOUT /T 3) is applied before the color scheme of the console is changed to provide visual feedback, indicating the next step or completion of the task.
# Important Notes:
# Security Concern: This script captures the user's email and password and writes them to a file in plain text. Storing passwords this way can be a significant security risk. It is important not to use this script in production environments where sensitive data security is a concern. You should not use actual user credentials or encourage others to do so.

# Educational Purpose: This script is primarily for educational purposes, demonstrating basic batch scripting techniques, such as capturing user input, using variables, and writing to files.😎
