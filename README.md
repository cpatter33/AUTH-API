# Auth API

A user authentication REST API bilt with FASTAPI, featuring password hashing with bcrypt and JWT-based session tokens for protected routes

## Features
- User registration with secure password hashing
- Login with JWT token generation
- Protected route to fetch current user
- SQLite database with SQLAlchemy ORM

## Tech Stack
- Python 
- FastAPI
- SQLAlchemy
- SQLite 
- Pydantic 
- Passlib (bcrypt)
- python-jose (JWT)

## How to run
1. Clone the repository 
2. Create a virtual enivornment: 'python -m venv venv'
3. Activate the virtual enviorment: 'venv\Scripts\activate'
4. Install dependencies: 'pip install -r requirements.txt'
5. Run the server: 'uvicorn main:app --reload'
6. Open 'http://localhost:8000/docs' to test the API
