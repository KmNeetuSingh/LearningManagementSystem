# Learning Management System ✨📚  

## Overview  
A sleek and responsive platform for secure user authentication and intuitive design, built with **HTML, CSS, and JavaScript**.  

## Features 🚀  

- **Responsive Design** 📱💻: Automatically adjusts to any screen size for a seamless experience.  
- **Form Validation** ✅: Ensures users input both email and password before login.  
- **Password Toggle** 👁️: Allows users to show or hide their password with a single click.  
- **Local Storage Authentication** 💾: Retrieves and verifies credentials from local storage for secure login.  
- **Google Sign-In Button** 🌐: Placeholder for future integration with Google login.  

## Technology Stack 💻  

- **HTML5**: For structuring the webpage.  
- **CSS3**: For stylish designs, including shadows, buttons, and layouts.  
- **JavaScript (ES6)**: For handling form logic and local storage interactions.  
- **Font Awesome**: For password visibility icons.  
- **Google Fonts**: For a modern, clean look.  

## Getting Started 🚧  

### Prerequisites 🔧  
- A modern web browser like **Google Chrome** or **Firefox**.  
- Basic knowledge of **HTML, CSS, and JavaScript**.  

### Installation 🛠️  

1. **Clone or Download** the project files:  
   ```bash  
   git clone <repository-url>  
   ```  

2. **Open the Project**:  
   Navigate to the folder and open `index.html` in your browser.  

### File Structure 📂  

```  
/project-root  
│  
├── index.html         # Main HTML file  
├── style.css          # CSS file for styling  
└── script.js          # JavaScript file for form validation and logic  
```  

### Functionality 💡  

1. **Login Form**:  
   - Users must enter an email and password.  
   - Validates input and matches credentials with local storage.  
   - Successful login redirects users to `course.html`.  

2. **Password Toggle** 👁️:  
   - Click the eye icon to toggle password visibility.  

3. **Login Validation** ✅:  
   - Displays error messages for incorrect email or password.  

## Usage 📝  

1. **Adding Users**:  
   - Use browser developer tools to store user credentials in local storage:  
     ```javascript  
     localStorage.setItem("allAdmin", JSON.stringify([{ email: "admin@example.com", password: "admin123", name: "Admin", id: 1 }]));  
     localStorage.setItem("allUser", JSON.stringify([{ email: "user@example.com", password: "user123", name: "User", id: 2 }]));  
     ```  

2. **Sign-In**:  
   - Enter a registered email and password to log in.  

3. **Password Visibility**:  
   - Use the toggle button to view or hide your password.  

## Future Enhancements 🌟  

- **Google Sign-In Integration** 🌐: Enable users to log in with their Google accounts.  
- **Backend Integration** 💾: For enhanced security and functionality.  
- **Sign-Up Functionality** 📝: A dedicated page for new user registration.  

## Acknowledgments 🙏  

- **Font Awesome** for the password toggle icons.  
- **Google Fonts** for the modern font design.  

---  
