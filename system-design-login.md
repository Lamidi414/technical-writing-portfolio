
# 📄 How a Login System Works (Simple Explanation)

# How a Login System Works

## Overview
A login system allows users to securely access an application using a username and password.

---

## Step-by-Step Process

### 1. User Enters Credentials
The user inputs:
- Username (or email)
- Password

---

### 2. Data is Sent to the Server
The application sends the credentials to the server for verification.

---

### 3. Server Checks the Database
The server:
- Looks for the user in the database
- Compares the entered password with the stored password

---

### 4. Authentication Result

#### If Correct:
- User is granted access
- A session or token is created

#### If Incorrect:
- Access is denied
- Error message is shown

---

## Simple Flow Diagram
```
User → Login Form → Server → Database
↓
Access Granted / Denied
```

---

## Security Notes
- Passwords should be encrypted (hashed)
- Use HTTPS to protect data
- Limit login attempts to prevent attacks

---

## Conclusion
A login system ensures only authorized users can access an application.
