# EA Inventory System

## Architecture Document

**Version:** 1.0
**Status:** Approved
**Last Updated:** June 2026

---

# 1. Purpose

This document describes the high-level architecture of EA Inventory System and the rationale behind the selected architectural decisions.

The architecture is designed to support the MVP while maintaining simplicity, maintainability and future scalability.

---

# 2. Architectural Goals

The system must:

- Be easy to understand and maintain.
- Support future business growth.
- Allow future expansion into a SaaS platform.
- Minimize technical complexity during MVP development.
- Be suitable for a solo developer.

---

# 3. Architectural Style

EA Inventory System follows a Modular Monolith architecture.

The application is divided into logical modules while remaining a single deployable application.

---

# 4. High-Level Architecture

Frontend
↓
React Application
↓
REST API
↓
Node.js + Express
↓
Prisma ORM
↓
MySQL Database

---

# 5. Architectural Rationale

## Why a Modular Monolith?

Benefits:

- Simpler development process.
- Easier deployment.
- Lower infrastructure requirements.
- Better suited for MVP development.

Trade-offs:

- Lower scalability compared to microservices.
- Requires future refactoring if the product grows significantly.

---

# 6. Future Evolution

The architecture should support future migration toward:

- Multi-company environments.
- SaaS architecture.
- Additional business modules.
- Cloud deployments.

These concerns are intentionally excluded from the MVP implementation.
