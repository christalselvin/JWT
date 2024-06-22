# Flask JWT Authentication Example

This is a simple Flask application that demonstrates how to implement JWT (JSON Web Token) authentication.

## Features

- User login with JWT authentication.
- Token generation upon successful login.
- Token expiration set to 1 hour.

## Requirements

- Python 3.12
- Flask
- PyJWT
## Install the required packages:

pip install Flask PyJWT
## Usage
python app.py
## Endpoints
/login (POST)
This endpoint is used to log in a user and generate a JWT token.

Request Body:

json
Copy code
{
  "username": "arun",
  "password": "arun"
}
Response:

On successful login:

json
Copy code
{
  "token": "your_jwt_token"
}
On invalid credentials:

json
Copy code
{
  "message": "Invalid credentials"
}
## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/flask-jwt-auth-example.git
   cd flask-jwt-auth-example

