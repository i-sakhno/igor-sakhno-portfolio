# Telegram Bot Platform

A Python-based Telegram bot platform developed as a personal
engineering project.

The project started as a simple booking bot and evolved into a
small backend system with user management, services, bookings,
administrative functionality and external integrations.

---

## 🎯 Project Overview

The platform supports two main use cases:

- appointment booking
- food ordering

The system includes separate user and administrator workflows,
persistent data storage, booking management and external calendar
integration.

The project was designed with a focus on maintainability,
separation of responsibilities and real-world business logic.

---

## 🏗️ Architecture

The application is built with Python and follows a modular
architecture separating Telegram handlers, business logic,
database access and external integrations.

### Main components

- Telegram Bot
- FSM-based user flows
- Service layer
- Database layer
- Google Calendar integration
- Administrative interface
- Booking management
- Client management

High-level structure:

```text
Telegram User
      │
      ▼
Telegram Bot / Handlers
      │
      ▼
Service Layer
      │
      ├── Booking Service
      ├── Client Service
      ├── Service Management
      └── Calendar Service
      │
      ▼
SQLite Database
      │
      ├── Clients
      ├── Services
      └── Bookings

External Integration
      │
      └── Google Calendar


## 💡 What This Project Demonstrates

This project demonstrates my ability to work beyond traditional
test automation and understand software from an engineering
perspective.

It combines:

- Backend development
- Database design
- API integrations
- Asynchronous programming
- Business logic
- Infrastructure
- Testing
- Automation