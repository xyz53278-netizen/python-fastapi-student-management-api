# python-fastapi-student-management-api
Student Management REST API built with FastAPI and SQLite, featuring CRUD operations, API-key authentication, Pydantic validation, and Pytest endpoint tests.
# 🚀 Python Application Development — Student Management REST API

A REST API built using **Python, FastAPI, SQLite, and SQLAlchemy** to demonstrate backend application development, database integration, CRUD operations, API authentication, and endpoint testing.

## ✨ Features

- Create, read, update, and delete student records
- SQLite database integration
- RESTful API endpoints using HTTP methods
- API-key authentication for protected operations
- Pydantic schema validation
- Duplicate email validation
- Automatic interactive API documentation
- Automated endpoint tests with Pytest

## 🛠️ Tech Stack

- Python
- FastAPI
- SQLite
- SQLAlchemy
- Pydantic
- Pytest
- HTTPX

## 📂 Project Structure

```text
python-application-development-api/
├── app.py
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
└── tests/
    └── test_app.py
```

## ⚙️ Installation

```bash
python -m venv .venv
.venv\Scripts\activate
python -m pip install -r requirements.txt
```

Start the API:

```bash
uvicorn app:app --reload
```

Open **http://127.0.0.1:8000/docs** to explore and test the endpoints.

## 🌐 API Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| GET | `/students` | Retrieve all students |
| GET | `/students/{student_id}` | Retrieve one student |
| POST | `/students` | Create a student |
| PUT | `/students/{student_id}` | Update a student |
| DELETE | `/students/{student_id}` | Delete a student |

POST, PUT, and DELETE require the `X-API-Key` header.

## 🧪 Run Tests

```bash
python -m pytest -q
```

## 🎯 Learning Outcomes

- Understand API routing and HTTP methods
- Connect a Python application to SQLite
- Perform CRUD operations
- Validate request data using Pydantic
- Implement basic API-key authentication
- Test endpoints and HTTP error responses

## 🔐 Security Note

This is an educational project. Configure a strong API key using an environment variable before sharing or deploying the application. Do not commit real secrets to GitHub.

## 👨‍💻 Author

**Kamal Dhaka**  
B.Tech Artificial Intelligence & Data Science Student

---

⭐ If this project helps you learn backend development, consider starring the repository!
