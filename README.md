# VRV Security - RBAC Web Application
This is a web application built using the MERN stack to demonstrate Role-Based Access Control (RBAC). It is designed for a security service company, where different user roles (Guard, Manager, and Authority) have access to specific services.

# Features
# 1. Authentication
Secure login system using JWT (JSON Web Tokens).
Ensures users are properly authenticated before accessing the system.
# 2. Authorization
Access to services depends on the user's role.
Each role has specific permissions.
# 3. User Roles
Guard: Can access limited features like CCTV surveillance.
Manager: Can manage guard deployment and view attendance records.
Authority: Has full access, including managing active units.
# Technologies Used
Frontend
React.js: For building the user interface.
Backend
Node.js and Express.js: For handling the backend logic and API endpoints.
Database
MongoDB: For storing user data, roles, and permissions.
Security
JWT (JSON Web Tokens): For secure user sessions.
bcrypt.js: For hashing and securely storing passwords.
# How It Works
User Authentication:

Users log in using their credentials.
The system verifies their details and issues a token.
# Role-Based Access Control (RBAC):

Each user has a specific role: Guard, Manager, or Authority.
The system checks the user's role before granting access to any service.
# Setup Instructions
Clone the repository:

git clone https://github.com/yourusername/your-repository.git

# Install dependencies:

cd your-repository
npm install
Start the application:

npm start
