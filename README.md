# SupportDesk

> Customer support with ticketing, live chat, and knowledge base

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
Angular, TypeScript, NestJS, Stripe, PostgreSQL

## 🏗️ Architecture
Backend service with Angular, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/supportdesk
cd supportdesk

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
