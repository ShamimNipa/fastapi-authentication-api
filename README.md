# FastAPI Authentication API

A REST API project built with FastAPI to demonstrate user authentication and authorization using JWT tokens, password hashing, SQLAlchemy, and MySQL.

## Features

- User authentication and authorization
- Password hashing
- JWT access tokens
- SQLAlchemy database integration
- Interactive API documentation with Swagger UI

## Tech Stack

- Python
- FastAPI
- SQLAlchemy
- MySQL
- PyMySQL
- JWT
- Passlib

## Requirements

- Python
- MySQL Server
- pip

## Setup

1. Clone this repository.
2. Create and activate a virtual environment.
3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Configure your MySQL database connection in `auth/database.py`.
5. Start the application:

   ```bash
   python -m uvicorn main:app --reload
   ```

6. Open `http://127.0.0.1:8000/docs` to explore the API.

## Database

This project currently uses MySQL. A running MySQL server and a correctly configured database connection are required to run the application.

## Note

This project is intended for learning and portfolio purposes.