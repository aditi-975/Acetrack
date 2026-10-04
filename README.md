
# Acetrack — Expense & Task Management System

Acetrack is a backend application designed to help users manage their expenses and tasks through secure RESTful APIs.

The project is built using Django and Django REST Framework, with JWT-based authentication and relational database support using PostgreSQL and SQLite. 

## Features

- User authentication and account management
- Expense tracking and category management
- Task creation and management
- Task priority and scheduling
- Focus session tracking
- Dashboard functionality
- Leaderboard functionality
- RESTful APIs using Django REST Framework 

## Tech Stack

- **Backend:** Django, Django REST Framework
- **Programming Language:** Python
- **Database:** PostgreSQL, SQLite
- **Authentication:** JWT
- **API:** RESTful APIs
- **Development Tools:** Git, GitHub, VS Code 

## Project Structure

```text
acetrack-backend/
│
├── agent/          # Agent-related functionality
├── config/         # Django project configuration
├── dashboard/      # Dashboard functionality
├── expenses/       # Expense management
├── focus/          # Focus session functionality
├── leaderboard/    # Leaderboard functionality
├── tasks/          # Task management
├── users/          # User management and authentication
│
├── manage.py       # Django management script
├── requirements.txt
├── .gitignore
└── README.md 

## Authentication

Acetrack uses **JWT (JSON Web Token) authentication** to secure API endpoints.

Authenticated users can access protected resources by providing a valid JWT access token with their API requests.

## API Functionality

The application provides RESTful APIs for:

- User management
- Expense management
- Task management
- Focus sessions
- Dashboard data
- Leaderboard data

The APIs support standard CRUD operations where applicable. 

## API Endpoints

| Module | Purpose |
|---|---|
| Users | User registration, authentication and account management |
| Expenses | Create, view, update and delete expenses |
| Tasks | Create, view, update and manage tasks |
| Focus | Manage focus sessions |
| Dashboard | Access dashboard-related data |
| Leaderboard | Access leaderboard-related data |

The API follows REST principles and uses Django REST Framework for request handling, serialization and validation. 

## Database

Acetrack supports both **PostgreSQL** and **SQLite** for database management.

- **PostgreSQL:** Recommended for production environments
- **SQLite:** Useful for local development and testing

Django ORM is used to define models and interact with the database. 

