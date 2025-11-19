Module 11 – FastAPI Calculator with PostgreSQL & Docker

This project implements a fully containerized FastAPI application that performs basic calculator operations (add, subtract, multiply, divide) with a PostgreSQL backend and pgAdmin for database management. It includes unit tests, end-to-end (E2E) tests, Dockerized infrastructure, and CI-ready organization.

📁 Project Structure
module11_is601/
│
├── app/
│   ├── operations/          # Calculator logic
│   ├── models/              # Database models
│   ├── schemas/             # Pydantic schemas
│   ├── core/                # Config
│   └── database.py          # DB connection
│
├── templates/               # index.html
├── tests/                   # unit + e2e tests
├── Dockerfile
├── docker-compose.yml
├── main.py                  # FastAPI app
└── requirements.txt

🚀 Features

FastAPI backend with auto-docs (Swagger & Redoc).

PostgreSQL database running in Docker.

pgAdmin web interface for DB management.

Fully tested:
✔ 68+ unit tests
✔ E2E tests with live FastAPI server
✔ 93%+ test coverage

Hot reload with Uvicorn.

Clean folder structure suitable for deployments.

🔧 Technologies Used

FastAPI

Python 3.10

PostgreSQL 15

pgAdmin 4

Docker & Docker Compose

Pytest + Coverage

Pydantic

🐳 Run the Project (Docker)

Make sure Docker Desktop is running.

Start the full stack
docker compose up --build

Services:
Service	URL
FastAPI	http://localhost:8000

API Docs	http://localhost:8000/docs

pgAdmin	http://localhost:5050

PostgreSQL	localhost:5432
🧪 Run Tests (Local Venv)

Activate your venv:

source venv/bin/activate


Run all tests:

pytest -q


Run E2E tests only:

pytest tests/e2e/test_e2e.py -q


Generate coverage:

pytest --cov=app


Coverage HTML opens at:

htmlcov/index.html

🗄 PostgreSQL Credentials

Used by Docker + pgAdmin:

POSTGRES_USER=postgres
POSTGRES_PASSWORD=postgres
POSTGRES_DB=fastapi_db


pgAdmin login:

Email: admin@example.com
Password: admin

📌 Endpoints
GET /

Returns index.html UI.

POST /add
POST /subtract
POST /multiply
POST /divide

Format:

{
  "a": 5,
  "b": 7
}

📬 Author

Megha Saju
Business & Information Systems / Information Systems MS
NJIT – IS601 Assignment Module 11