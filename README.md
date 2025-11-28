# support-ticket-system

## Goal
A realistic backend project to practice Spring Boot, Postgres, and production-style patterns by building a small internal support ticket system.

## Tech Stack
- Java 21
- Spring Boot
- Postgres
- JPA / Hibernate
- JUnit (later + Testcontainers)

## Phase 1 – MVP Features
- Users (CUSTOMER, AGENT, ADMIN)
- Tickets with severity & status
- Comments on tickets
- Basic filtering (status, severity, assignee, creator)
- Pagination

## Phase 2 – Next Features
- Ticket history / audit log
- SLA deadlines by severity
- Scheduled job to detect overdue tickets
- Advanced filters (date ranges)

## Phase 3 – Stretch
- Role-based access control
- Simple reporting endpoints
- Attachments model (file metadata)

## Long-term
Use this project as:
- A daily backend practice ground
- A place to try patterns (events, transactions, testing)
- A public log of progress
