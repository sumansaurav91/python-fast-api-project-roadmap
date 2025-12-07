# 30 FastAPI Projects: Beginner to Expert

## 🟢 Beginner (Projects 1-10)
*Focus: Routing, Pydantic models, path/query parameters, basic CRUD*

### 1. Hello World API
Basic GET endpoints returning JSON. Learn FastAPI setup, uvicorn, and automatic docs.

### 2. Calculator API
Endpoints for add, subtract, multiply, divide with query parameters. Practice parameter validation.

### 3. Random Data Generator
Generate random names, emails, passwords via endpoints. Learn response models and Pydantic.

### 4. Unit Converter
Convert temperature, length, weight units. Path parameters and input validation.

### 5. Todo API (In-Memory)
CRUD operations with a Python list/dict. Learn POST, PUT, DELETE, and status codes.

### 6. Contact Book API
Store and retrieve contacts. Practice Pydantic models with nested data and field validation.

### 7. Quote of the Day API
Return random quotes, filter by category. Query parameters and list operations.

### 8. BMI Calculator API
Calculate BMI with health category. Response models and computed fields.

### 9. URL Shortener (Basic)
Generate short codes, redirect to original URL. Learn RedirectResponse and simple persistence.

### 10. Dictionary/Thesaurus API
Word definitions and synonyms from a JSON file. File handling and error responses (404s).

---

## 🟡 Intermediate (Projects 11-20)
*Focus: Databases, authentication, file uploads, background tasks*

### 11. Notes API with SQLite
Full CRUD with SQLAlchemy. Learn ORM integration, database sessions, and migrations (Alembic).

### 12. User Registration System
Sign up with hashed passwords (bcrypt). Password hashing, email validation, and user models.

### 13. JWT Authentication API
Login, protected routes, token refresh. Learn OAuth2PasswordBearer and JWT tokens.

### 14. Blog API
Posts, categories, tags with relationships. SQLAlchemy relationships and complex queries.

### 15. File Upload Service
Upload, store, and serve images/documents. Learn File and UploadFile, static files, and storage.

### 16. Email Sending API
Send emails via SMTP with templates. Background tasks and external service integration.

### 17. Task Queue with Celery
Long-running jobs with status tracking. Background workers and async task processing.

### 18. REST API with Pagination
List endpoints with cursor/offset pagination. Query parameters, metadata responses, and performance.

### 19. API Rate Limiter
Limit requests per user/IP. Middleware, dependencies, and Redis for tracking.

### 20. Weather Aggregator
Fetch from multiple weather APIs, combine results. Async HTTP clients (httpx) and data aggregation.

---

## 🟠 Advanced (Projects 21-26)
*Focus: WebSockets, caching, testing, security, complex architectures*

### 21. Real-Time Chat Server
WebSocket-based chat rooms. Learn WebSocket endpoints, connection management, and broadcasting.

### 22. E-Commerce API
Products, cart, orders, payments (Stripe). Complex business logic, transactions, and webhooks.

### 23. OAuth2 Social Login
Login with Google/GitHub. OAuth2 flows, third-party providers, and token exchange.

### 24. API with Redis Caching
Cache expensive queries, invalidation strategies. Redis integration and cache patterns.

### 25. Multi-Tenant SaaS API
Isolated data per organization. Database schemas, tenant middleware, and access control.

### 26. Fully Tested API
Unit tests, integration tests, test database. pytest, TestClient, fixtures, and CI/CD integration.

---

## 🔴 Expert (Projects 27-30)
*Focus: Microservices, event-driven systems, production deployment*

### 27. Microservices with Message Queue
Multiple services communicating via RabbitMQ/Kafka. Service decomposition and async messaging.

### 28. GraphQL API with Strawberry
GraphQL layer over existing data. Learn Strawberry, resolvers, and GraphQL vs REST trade-offs.

### 29. ML Model Serving API
Deploy a trained model (sentiment analysis, image classification). Model loading, prediction endpoints, and batch processing.

### 30. Production-Ready API Template
Complete starter with:
- Async PostgreSQL (asyncpg + SQLAlchemy 2.0)
- JWT auth with refresh tokens
- Role-based permissions
- Request logging and tracing
- Health checks and metrics (Prometheus)
- Docker + docker-compose
- Alembic migrations
- Comprehensive test suite
- API versioning
- Documentation customization

---

## Key Concepts by Level

| Level | Concepts to Master |
|-------|-------------------|
| Beginner | Routes, Pydantic, validation, status codes, auto-docs |
| Intermediate | SQLAlchemy, JWT, dependencies, background tasks, async |
| Advanced | WebSockets, caching, testing, security, middleware |
| Expert | Microservices, message queues, deployment, observability |

---

## Tips for Learning FastAPI

1. **Use the interactive docs** — test endpoints at `/docs` constantly
2. **Read Pydantic docs** — 50% of FastAPI power comes from Pydantic
3. **Learn async Python** — understand `async/await` before project 15
4. **Use type hints everywhere** — FastAPI relies on them heavily
5. **Check the FastAPI source** — it's readable and educational
6. **Deploy early** — use Railway, Render, or a VPS to see real behavior
7. **Add OpenAPI descriptions** — practice documenting as you build

---

## Suggested Tech Stack Progression

```
Beginner:    FastAPI + Pydantic + uvicorn
Intermediate: + SQLAlchemy + SQLite → PostgreSQL + Alembic
Advanced:    + Redis + pytest + Docker
Expert:      + RabbitMQ/Kafka + Kubernetes + Prometheus
```
