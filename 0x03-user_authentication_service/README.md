# 0x03. User Authentication Service

## Overview

In this project, you will build a user authentication service using Flask. The service will handle user registration, login, logout, and session management. This project aims to teach you how to work with Flask to create API routes, manage cookies, handle request data, and return appropriate HTTP status codes.

## Learning Objectives

By the end of this project, you should be able to:

- Declare API routes in a Flask app.
- Get and set cookies in HTTP requests.
- Retrieve form data from requests.
- Return various HTTP status codes.
- Use SQLAlchemy for database interactions in a Flask app.
- Implement password hashing using `bcrypt`.

## Key Concepts

- **Flask**: A micro web framework for Python used to build web applications quickly and with a minimal amount of code.
- **SQLAlchemy**: An SQL toolkit and Object-Relational Mapping (ORM) library for Python, allowing for efficient and easy database manipulation.
- **Cookies**: Small pieces of data stored on the client-side and sent with HTTP requests to maintain session information.
- **HTTP Status Codes**: Codes returned by the server indicating the status of the HTTP request (e.g., 200 OK, 404 Not Found).

## Requirements

- Python 3.7
- Flask framework
- SQLAlchemy 1.3.x
- `bcrypt` for password hashing
- Code should follow the PEP 8 style guide (version 2.5)

## Setup

### Prerequisites

Ensure you have Python 3.7 installed on your system. You can verify your installation by running:

```bash
python3 --version

