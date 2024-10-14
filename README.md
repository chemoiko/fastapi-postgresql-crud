# FastApi Postgresql CRUD
This is a simple FastAPI-based application for managing books, using SQLAlchemy as the ORM (Object Relational Mapper) to interact with a PostgreSQL database. The app allows for creating, reading, updating, and deleting (CRUD) book records, with a focus on clean code, modularity, and scalability.

## Features 
- PostgreSQL Database Integration: Uses SQLAlchemy to connect to a PostgreSQL database.
- FastAPI for API Endpoints: A modern, fast (high-performance) web framework for building APIs.
- Data Models with Pydantic: Defines request and response schemas using Pydantic for easy validation and serialization.
- Book Management: CRUD operations for managing books, including title and description.

## Tech Stack
- FastAPI: A fast web framework for building APIs in Python 3.6+.
- SQLAlchemy: Python's SQL toolkit and ORM, used for database interactions.
- PostgreSQL: An open-source relational database system.
- Pydantic: Data validation and settings management using Python type annotatio

## How to run

1.  .\venv\Scripts\activate
2. cd .\app\
3. uvicorn main:app --reload
