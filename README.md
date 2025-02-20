# Form Validation and User Data Fetching

## Overview
This is a simple web-based form validation project that allows users to register by providing their name, email, and password. It includes real-time validation and stores user information in `localStorage`. Additionally, users can fetch a list of users from an external API (`https://jsonplaceholder.typicode.com/users`).

## Features
- Form validation with error messages
- Password strength validation
- Stores user details in `localStorage`
- Fetches and displays user data from an API
- Loading indicator for API requests

## Technologies Used
- HTML
- CSS
- JavaScript (ES6+)
- Fetch API
- LocalStorage

## How to Use
1. Open `index.html` in a browser.
2. Enter a name, valid email, and a strong password.
3. Submit the form to save data.
4. Click "Display Data" to fetch users from the API.

## Validation Rules
- **Email**: Must follow a standard email format.
- **Password**: At least 8 characters long, includes uppercase, lowercase, number, and special character.
- **Common Weak Passwords**: Rejected (e.g., "123456", "password", etc.).

## Local Storage
- User's name and email are saved and pre-filled when reopening the page.

## API Used
- `https://jsonplaceholder.typicode.com/users`

## License
This project is open-source and free to use.

