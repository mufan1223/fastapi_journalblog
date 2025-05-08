# 📝 FastAPI JournalBlog

A lightweight blog system built with FastAPI, supporting user registration, login, and full CRUD operations for articles. Ideal for learning FastAPI, JWT authentication, and SQLAlchemy ORM in a real-world scenario.

---

## 🚀 Features

- ⚡ High-performance asynchronous RESTful API with FastAPI
- 🧱 SQLAlchemy for database ORM with async support
- 🔐 JWT-based authentication system
- 📦 Dependency injection with FastAPI's DI system
- 🧩 Modular project structure for scalability
- 📄 Interactive API documentation (Swagger UI & Redoc)
- ✅ Unit tests with pytest
- 🔧 Environment configuration management

---
                                                    <!--by 许嘉辉 -->
## 🧰 Tech Stack

- **Python 3.8+**
- **FastAPI** - Web framework
- **Uvicorn** - ASGI server
- **SQLAlchemy** - ORM with async support
- **Pydantic** - Data validation
- **JWT** - JSON Web Token authentication
- **python-dotenv** - Environment variables
- **pytest** - Testing framework
- **alembic** (Optional) - Database migrations

---
                                                    <!--by 林俞帆 -->
## 📁 Project Structure

```text
fastapi_journalblog/
├── app/
│   ├── main.py              # Application entry point
│   ├── models/              # Database models
│   ├── routers/             # API route handlers
│   ├── schemas/             # Pydantic models
│   ├── services/            # Business logic layer
│   └── dependencies.py      # Auth dependencies
├── tests/                   # Test cases
├── alembic/                 # Database migrations (optional)
├── requirements.txt         # Project dependencies
├── .env.example             # Environment template
├── LICENSE
├── README.md
└── README.zh.md
                                                    <!--by 杨樊 -->    