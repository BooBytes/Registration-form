
# Registration Form

## Overview

This is a simple registration form implemented in HTML, CSS, and JavaScript. The form includes fields for name, email, and password, along with client-side validation to ensure the data is correctly entered before submission.

## Features

- **Real-time Validation**: Provides immediate feedback on the user’s input for each field.
  - **Name**: Checks that the name field is not empty.
  - **Email**: Validates that the input is in the correct email format.
  - **Password**: Ensures the password is at least 6 characters long.

- **Styling**: Basic styling for the form container and input fields to improve user experience.

## HTML Structure

- **Form Container**: Contains the entire form with a title and input fields.
- **Form Fields**:
  - **Name**: A text input for the user's name.
  - **Email**: An email input for the user's email address.
  - **Password**: A password input for the user's password.
- **Submit Button**: Submits the form after validation.

## CSS Styles

- **.form-container**: Centers the form on the page, applies background color, padding, and border.
- **.form-group**: Adds margin to each form group for spacing.
- **.error**: Styles error messages in red for visibility.
- **button**: Styles the submit button with a black background and white text.
- **#name, #email, #password**: Styles the input fields with padding and rounded corners.

## JavaScript Functions

- **validateName()**: Ensures the name field is not empty. Displays an error message if it is.
- **validateEmail()**: Checks if the email address is in the correct format. Displays an error message if it is not.
- **validatePassword()**: Validates that the password is at least 6 characters long. Displays an error message if it is not.
- **Event Listeners**: Attached to input fields to validate the data in real-time as the user types.
- **Form Submit Event**: Prevents form submission if any of the validation checks fail.

## Usage

1. **Open**: Load the HTML file in a web browser to view the registration form.
2. **Interact**: Enter data into the form fields and observe real-time validation feedback.
3. **Submit**: Click the "Register" button to submit the form. If any field is invalid, the form will not submit, and error messages will be displayed.


