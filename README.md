# Base_Campy

📌 Introduction

Base Campy – Authentication Service is a secure backend API focused on user authentication and account management.
The project demonstrates a production-ready auth system using modern backend practices such as JWT-based authentication, secure cookies, email verification, and password recovery workflows.

This project intentionally limits scope to authentication-related CRUD operations to emphasize security, correctness, and clean backend architecture.

✨ Core Features
🔐 Authentication & Account Management

User registration with email verification
Secure login with JWT & refresh tokens
Logout with token invalidation
Password hashing using bcrypt
Secure token generation using crypto
Cookie handling with cookie-parser
Forgot & reset password flow
Resend email verification support
Role-ready architecture for future expansion

🔗 API Routes
Authentication Routes (/api/v1/users)
Method	Endpoint	Description
POST	/register	Register a new user
POST	/login	Authenticate user
POST	/logout	Logout current user
GET	/current-user	Fetch logged-in user
POST	/change-password	Change account password
POST	/refresh-token	Refresh access token
GET	/verify-email/:token	Verify email address
POST	/forgot-password	Request password reset
POST	/reset-password/:token	Reset password

🛠 Tech Stack

Node.js
Express.js
MongoDB
JWT Authentication
cookie-parser
bcrypt
crypto
Mailgen
Nodemailer

🎯 Project Focus

This project is designed to demonstrate:
Secure authentication flows
Token-based session management
Email-driven account verification
Backend security best practices
Clean and modular API design
