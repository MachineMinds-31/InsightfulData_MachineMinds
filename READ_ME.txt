# User Information Collector

This Python script collects basic user information, including the first name, second name, phone number, and Gmail address. It validates the input to ensure the provided phone number and email address meet specified criteria.

## Features

- Prompts the user to enter their first and second names.
- Validates the phone number to ensure it is exactly 10 digits.
- Validates the Gmail address to ensure it ends with `@gmail.com` and contains only alphanumeric characters before the `@` symbol.
- Displays the collected information if valid.

## Code Explanation

1. **Name Input:** 
   - The script collects the user's first and second names and capitalizes them for proper formatting.

2. **Phone Number Validation:**
   - Checks that the phone number is exactly 10 digits long and contains only numeric characters.
   - If valid, it displays the phone number; otherwise, it prompts an error message.

3. **Email Validation:**
   - Ensures that the email ends with `@gmail.com` and the username before it is alphanumeric.
   - If valid, it displays the email; otherwise, it prompts an error message.

## Usage

To run this script, simply execute it in a Python environment. You will be prompted to enter your first name, second name, phone number, and Gmail address. The script will provide feedback based on your input.

```bash
python user_info_collector.py

Requirements
Python 3.x