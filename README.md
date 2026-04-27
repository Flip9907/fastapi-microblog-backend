# read documentation
# FastAPI Microblogging Backend

## Overview
This project is a backend API built using FastAPI that supports user authentication and post management features similar to a microblogging platform.

## Features
- User registration and login
- JWT-based authentication
- Create, update, delete posts
- Secure API endpoints

## Tech Stack
- Python
- FastAPI
- PostgreSQL
- SQLAlchemy
- JWT Authentication

## API Endpoints
- POST /users/ - Register user
- POST /login - Authenticate user
- GET /posts - Get all posts
- POST /posts - Create post

## How to Run
```bash
pip install -r requirements.txt
uvicorn main:app --reload
