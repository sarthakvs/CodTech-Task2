# CodTech-Task2
NAME: SARTHAK SUNDRIYAL

COMPANY: CODTECH IT SOLUTIONS

ID: CT08DS285


DOMAIN: BACKEND WEB DEVELOPMENT


DURATION: DECEMBER 5th, 2024 to JANUARY 5th, 2025


MENTOR: Muzammil Ahmed












**Overview of this project:**

Project Name:
Secure User Authentication System

Objective:
To design and implement a secure user authentication system that allows users to register, log in, and manage their accounts while ensuring password security and protected access to resources.

Key Features and Functionalities:

User Registration:

Users can create an account by providing a username and password.
Passwords are securely hashed using bcrypt before being stored.
User Login:

Users authenticate by providing valid credentials.
A JSON Web Token (JWT) is generated for session management.
Protected Routes:

Access to specific resources requires authentication via a valid JWT.
Password Update:

Authenticated users can update their password securely.
Account Deletion:

Users can delete their account permanently after authentication.
Profile Retrieval:

Authenticated users can view their profile information.
Technologies Used:

Framework: Express.js (Node.js)
Security:
bcrypt for password hashing
jsonwebtoken for token-based authentication
Middleware: Custom authentication middleware to verify JWTs
Data Storage: In-memory data store (for simplicity)
Key Activities:

Setup:

Initialize a Node.js project and configure Express.js.
Install required packages (bcrypt, jsonwebtoken, etc.).
Development:

Implement routes for user registration, login, and authentication.
Add functionality for password updates, account deletion, and profile retrieval.
Testing:

Verify all routes and features work as expected.
Test authentication flows, including token expiration and invalid credentials.
Deployment:

Prepare the application for deployment (optional).
Expected Outcomes:

A functional and secure API for user authentication.
Understanding of password hashing, token-based authentication, and session management.
Knowledge of handling protected routes and user account management.



Output:
1. POST: Register a new user -
   ![image](https://github.com/user-attachments/assets/fe8f6369-20d4-476a-ae78-6c7cf9593b86)
2. POST: Login a user -
  ![image](https://github.com/user-attachments/assets/a144262f-fc9b-4433-a465-ba55ad2f6b86)
3. GET: Protected route -
   ![image](https://github.com/user-attachments/assets/76550fcc-18c0-47f1-b7c1-739f6aa3e267)
4. PUT: Update user password -
   ![image](https://github.com/user-attachments/assets/f282ae40-399d-48d8-98de-650b0e0f1af0)
5. DELETE: Delete user account -
   ![image](https://github.com/user-attachments/assets/b780e034-22b5-42d0-9fa3-278585370077)
6. GET: Fetch user profile -
   ![image](https://github.com/user-attachments/assets/19b8f51e-53b9-472a-9a93-f9d181599df0)




