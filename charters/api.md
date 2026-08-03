# Project Charter - API

**Last Updated**: [Date]
**Version**: 1.0.0
**Status**: In Progress

---

## 1. Project Identification

| Field                  | Value                           |
| ---------------------- | ------------------------------- |
| **Project Name**       | API                             |
| **Project Repo**       | quran-api                       |
| **Project Manager**    | [nyzd](https://github.com/nyzd) |
| **Development Team**   | Backend                         |
| **Start Date**         | 2025-02-24                      |
| **Estimated End Date** |                                 |

---

## 2. Vision and Goals

### Vision

TBD

### High-Level Goals

TBD

---

## 3. Project Scope

### In-Scope

- Islamic data including:
  - quran
- Account management
- Token-based authentication
- Role-based access control (e.g., free tier vs. authenticated)
- Stateless architecture to support horizontal scaling.
- Monitoring and health-check endpoints.

### Out-of-Scope

TBD

---

## 4. Architecture & Technologies

### Backend

- **Language**: Python
- **Framework**: Django (RESTful API)
- **Coding Standards**: backend-standards
- **Database**: PostgreSQL
- **Broker**:

#### API Routers

- API Controller/Action name
- API Controller/Action name
- API Controller/Action name

#### DB Tables

- Table name (Use case)
  - related to...
  - related to...
- Table name (Use case)
  - related to...
  - related to...

### Infrastructure

- **CI/CD**: GitHub Actions
- **Hosting**:
  - Single standalone server (Linux) running Docker
- **Docker available containers**:
  - Django API
  - PostgreSQL

---

## 5. Pending Decisions

TBD

---

## 6. Timeline

TBD

---

## 7. Risks & Challenges

TBD

---

## 8. Success Metrics

TBD

---

## 9. Budget & Resources

- **Human Resources**: 1 developer
- **Hardware/Software Resources**: 1 server

---

## 10. Approval Signatures

| Role            | Github Account                                    |
| --------------- | ------------------------------------------------- |
| Curator         | [Al-Abd](https://github.com/al-abd)               |
| DevOps          | [codebysilence](https://github.com/codebysilence) |
| Project Manager |                                                   |
