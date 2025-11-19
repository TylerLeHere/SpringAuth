## Overview

This Spring Boot application provides a full authentication flow, including:

- **User signup with email verification**
- **User login with JWT token generation**
- **Email verification workflow** (send code → verify user)
- **Fetching authenticated user profile**
- **Basic error handling and logging**

The backend is integrated with **Supabase** for database storage and user management.

---

## Features

- **User Signup** – register with email and password  
- **Email Verification** – send verification email with code, verify account  
- **User Login** – authenticate and receive JWT token  
- **Fetch User Details** – access secured endpoints with JWT  
- **Error Handling** – simple exception handling and logging  

---

## Prerequisites

Before running the project, make sure you have the following installed:

- **Java Development Kit (JDK) 8 or higher**  
- **Maven** (or Gradle) for dependency management  
- **Supabase account & database**  
- **Postman** (or any API client) for testing endpoints
