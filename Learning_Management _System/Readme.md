# Learning Management System

## Overview

This project is a **LearningManagementSystem** built using HTML, CSS, and JavaScript. It allows users to log in using their email and password. It validates the input fields and checks for user credentials stored in the browser's local storage. The design is simple yet functional, with a clean and responsive UI.

## Features

- **Responsive Design**: The layout adjusts based on the screen size.
- **Form Validation**: Ensures users input both email and password before submitting.
- **Password Toggle**: Users can show or hide their password by clicking an eye icon.
- **Local Storage Authentication**: User data is retrieved from local storage to verify login credentials.
- **Google Sign-In Button**: A placeholder button for Google sign-in integration (not functional in this example).

## Technology Stack

- **HTML5**: Structuring the webpage.
- **CSS3**: Styling the webpage, including shadows, button styles, and layout.
- **JavaScript (ES6)**: Handling form submissions, password toggle, and local storage interaction.
- **Font Awesome**: Icons for the password visibility toggle.
- **Google Fonts**: Custom font for a modern look.

## Getting Started

### Prerequisites

- A web browser (Google Chrome, Firefox, etc.).
- Basic understanding of HTML, CSS, and JavaScript.

### Installation

1. **Clone or download the project files**:
   ```bash
   git clone <repository-url>
   ```

2. **Open the project**:
   Navigate to the project folder and open `index.html` in your browser.

### File Structure

```
/project-root
│
├── index.html         # Main HTML file for the sign-in page
├── style.css          # Embedded CSS in the HTML for page styling
└── script.js          # Embedded JavaScript in the HTML for form validation and login logic
```

### Functionality

1. **Login Form**:
    - Users must enter an email and password.
    - The form validates if both fields are filled before submission.
    - On submission, it checks the user credentials against local storage (`allAdmin` for admins and `allUser` for students).

2. **Password Toggle**:
    - Users can show or hide the password by clicking the eye icon next to the password field.

3. **Login Validation**:
    - If the email and password match the data stored in local storage, the user is logged in successfully and redirected to the `course.html` page.
    - Error messages are displayed for incorrect email, password, or both.

## Usage

1. **Adding Users**:
    - The script assumes user data (email, password, name, and ID) are already stored in local storage under the keys `allAdmin` (for admins) or `allUser` (for students).
    - You can manually add users to local storage using the browser’s developer tools:
      ```javascript
      localStorage.setItem("allAdmin", JSON.stringify([{ email: "admin@example.com", password: "admin123", name: "Admin", id: 1 }]));
      localStorage.setItem("allUser", JSON.stringify([{ email: "user@example.com", password: "user123", name: "User", id: 2 }]));
      ```

2. **Sign-In**:
    - Enter a registered email and password.
    - Click **Sign In** to log in.
    - If successful, the user is redirected to the `course.html` page.

3. **Password Visibility**:
    - Click the eye icon next to the password field to toggle password visibility.

## Future Enhancements

- **Google Sign-In Integration**: Add functionality for users to sign in using Google.
- **Backend Integration**: Connect the form to a backend server for more secure authentication.
- **Sign-Up Functionality**: Add a dedicated sign-up page for new users.

## Acknowledgments

- Font Awesome for the eye icon.
- Google Fonts for the **Hind Siliguri** font.