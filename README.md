# Product-Management-clean-architecture-demo

# Overview

This repository demonstrates a clean architecture implementation for a product management system. It showcases separation of concerns, maintainability, and testability through well-defined architectural layers.

# Architecture Layers

```bash
┌───────────────────────┐
│      Presentation     │  (UI/API Layer)
└───────────┬───────────┘
            │
┌───────────▼───────────┐
│     Application       │  (Use Cases/Logic)
└───────────┬───────────┘
            │
┌───────────▼───────────┐
│       Domain          │  (Business Models/Rules)
└───────────┬───────────┘
            │
┌───────────▼───────────┐
│     Infrastructure    │  (Persistence/External)
└───────────────────────┘
```

# Features

- Product Management: Create, read, update, and delete products

- Validation: Business rule enforcement

- Persistence: Database integration

- API: RESTful endpoints

# Technologies

- Backend: [.NET Core] 

- Database: [SQL Server] 



