# ApeStock — Warehouse Management System

A full-stack warehouse management application built as a learning project to develop and demonstrate skills in modern software engineering, testing, CI/CD, and project management.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React, TypeScript |
| Backend | Java 17+, Spring Boot |
| Database | PostgreSQL |
| Testing | |
| CI/CD |  |
| Containerization | Docker, Docker Compose |

---

## Features (Planned)

- Product and SKU management
- Stock level tracking and adjustments
- Inbound / outbound shipment records
- Warehouse location and bin management
- Low-stock alerts
- Audit trail / change history
- User authentication and role-based access control
- REST API with OpenAPI documentation

---

## Project Goals

This project is being built collaboratively to strengthen practical skills across the full software development lifecycle:

- **Full-stack development** — React frontend communicating with a Spring Boot REST API backed by PostgreSQL
- **Testing** — unit tests, integration tests, and end-to-end tests with meaningful coverage targets
- **CI/CD** — automated build, test, and deployment pipelines using GitHub Actions
- **Project management** — working in iterations with issues, pull requests, and code reviews
- **Software design** — domain modeling, layered architecture, and API design
- **DevOps** — containerised development and deployment with Docker

---

## Getting Started

### Prerequisites

- Java 17+
- Node.js 18+
- Docker and Docker Compose
- PostgreSQL (or use the Docker Compose setup)

### Run with Docker Compose

```bash
docker compose up --build
```

This starts the database, backend, and frontend together.

### Run locally

**Backend**

```
```

**Frontend**

```bash
cd frontend
npm install
npm run dev
```

The API will be available at `http://localhost:8080` and the frontend at `http://localhost:5173`.

---

## Project Structure

```
apestock/
├── backend/          # Spring Boot application
│   ├── src/
│   └── pom.xml
├── frontend/         # React application
│   ├── src/
│   └── package.json
├── docker-compose.yml
└── README.md
```

---

## API Documentation


```
```

---

## Contributing

This is a three-person project. All changes go through pull requests and must pass CI checks before merging. Branch naming convention:

- `feat/description` — new features
- `fix/description` — bug fixes
- `chore/description` — maintenance tasks

---

## Authors

- [IamLeila](https://github.com/IamLeila)
- [Morimoto](https://github.com/davidhuszardev)
- [opa](https://github.com/opa)


---

## License

MIT
