# Password Generator Project

## Overview
This project is a simple password generator web application. It allows users to generate a random password based on selected criteria and copy it to the clipboard.

## Features
- Generate a random password with customizable options:
  - Include uppercase letters
  - Include lowercase letters
  - Include numbers
  - Include symbols
- Copy the generated password to the clipboard
- Reset the form to its default state

## Technologies Used
- HTML
- CSS (Tailwind CSS)
- JavaScript

## How to Use
1. Open the `index.html` file in a web browser.
2. Set the desired password length and select the criteria for the password (uppercase, lowercase, numbers, symbols).
3. Click the "Generate" button to create a password.
4. Click the "Copy To Clipboard" button to copy the generated password.
5. Click the "Refresh" button to reset the form and clear the generated password.

## Functions
### `generatePassword()`
- This function generates a random password based on the selected criteria and sets the value of the password input field.

### `copyPassword()`
- This function selects the password field and copies its value to the clipboard. An alert is shown to confirm that the password has been copied.

### `resetForm()`
- This function resets all form fields to their default state and clears the generated password.

## Setup
1. Create an HTML boilerplate using `shift + !`.
2. Link the HTML file with Tailwind CSS.
3. Create the layout of the page using HTML and Tailwind CSS.
4. Add the `generatePassword()`, `copyPassword()`, and `resetForm()` functions in JavaScript.

## License
This project is open-source and available under the [MIT License](LICENSE).