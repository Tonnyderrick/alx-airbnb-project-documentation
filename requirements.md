# Backend Feature Requirements - ALX Airbnb Project

This document outlines the technical and functional requirements for three core backend features of the ALX Airbnb project.

---

## 1. User Authentication

### Overview:
Handles user registration, login, logout, and token-based authentication.

### API Endpoints:
- `POST /api/auth/register/`: Register a new user.
- `POST /api/auth/login/`: Authenticate user and return token.
- `POST /api/auth/logout/`: Invalidate current user session.
- `GET /api/auth/profile/`: Retrieve authenticated user profile.

### Input Specifications:
#### Register:
```json
{
  "username": "johndoe",
  "email": "john@example.com",
  "password": "securePass123"
}
