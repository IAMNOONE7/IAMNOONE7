I'm a software developer with **5 years of professional experience** and around **12 years of coding experience**, starting in high school, continuing through college, and now in industry.

My main languages are **C#** and **Python**, but I have worked across a broad technical range — from **Assembly**, **C**, **C++**, **VBA**, **SQL**, and **TypeScript** to **PLC programming**, **VHDL**, and **MATLAB**.

At both international companies where I have worked, I gradually took on **development leadership responsibilities**. I currently act as the **technical owner of C# development**, responsible for architectural decisions, technical direction, and overall solution quality.

---

## Tech Stack

### Main

![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### Frameworks, Databases & Infrastructure

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![MSSQL](https://img.shields.io/badge/MS%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Also Worked With

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![VBA](https://img.shields.io/badge/VBA-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

My experience also includes industrial automation, engineering tools, and data systems.

---

## Projects

My current development work focuses on **HomeData** and **ShopForge**. **TradingLenses** remains live but is not currently under active development.

### HomeData — Utility Consumption Platform

**Status: Active development** · [domacidata.cz](https://domacidata.cz)

A platform for collecting and analysing household **water, electricity, and gas consumption**. It connects meter readings with dashboards that help users understand their usage, costs, and consumption patterns.

The project brings together device data ingestion, historical data processing, and a web application for exploring the results.

| Area | Technology |
|---|---|
| Backend | Python, FastAPI |
| Frontend | React, TypeScript |
| Database | PostgreSQL |
| Data ingestion | Azure IoT Hub, Azure Functions |
| Hosting | Azure |

Key areas include:

- Device registration and association with user accounts
- Consumption overviews and detailed historical charts
- Hourly, daily, and monthly data aggregation
- Cost calculations based on configurable utility prices
- Consumption patterns, trends, and peak usage analysis

### ShopForge — Multi-Store E-Commerce Platform

**Status: Active development** · [GitHub repository](https://github.com/IAMNOONE7/ShopForge)

A **multi-store e-commerce platform** where one ASP.NET Core backend and a shared React storefront serve independent stores, each with its own domain, branding, catalog, and configuration.

New stores are provisioned through **configuration and data, without a separate deployment**. The platform uses a modular monolith with shared infrastructure and isolation between tenants and stores.

| Area | Technology / Approach |
|---|---|
| Backend | C#, .NET 10, ASP.NET Core minimal APIs |
| Frontends | React, TypeScript, Vite — storefront and admin portal |
| Database | PostgreSQL, Entity Framework Core |
| Architecture | Modular monolith, shared-database multi-tenancy, transactional outbox |
| Testing | xUnit, Testcontainers, architecture tests, end-to-end test harness |
| Infrastructure | Azure Container Apps, Front Door, Blob Storage, Key Vault |
| Tooling | Docker Compose, GitHub Actions, Bicep |
| Observability | OpenTelemetry traces and business metrics |

Implemented capabilities include:

- Hostname-based store resolution, DNS ownership verification, and tenant isolation enforced in application code and database constraints
- Shared products and warehouse stock, with per-store listings, pricing, typed attributes, dynamic filters, and Excel imports
- Guest and customer checkout, stock reservations, signed Stripe payment webhooks, and idempotent checkout and refund requests
- Discount codes, VAT calculations, PDF invoices, returns, refunds, and credit notes
- Staff invitations, roles, session invalidation, and two-factor authentication for staff and platform operators
- Transactional email through Mailgun, background processing with retries, and an append-only audit trail
- Customer data export and erasure, consent records, and data retention workflows

Azure infrastructure and deployment automation are defined in code; the Azure deployment has not yet been run.

### TradingLenses — Financial Analytics Platform

**Status: Live; not currently under active development** · [tradinglenses.com](https://www.tradinglenses.com)

A full-stack financial analytics platform built with **FastAPI** and **React**, bringing together company fundamentals, market data, insider trading activity, and financial comparisons.

The platform is live and available online. My current development focus has shifted to HomeData and ShopForge.

| Area | Technology |
|---|---|
| Backend | Python, FastAPI |
| Frontend | React 19, TypeScript |
| Database | PostgreSQL |
| ORM | SQLAlchemy |
| Authentication | JWT with secure refresh-token rotation |
| Styling | Tailwind CSS + custom design-token system |
| Architecture | Layered architecture, repository pattern, dependency injection |
| Infrastructure | Azure |

Platform features include:

- Company overviews, financial statements, and fundamental analysis
- Company and sector comparisons
- Price charts and market sentiment dashboards
- Insider trading data and aggregated activity
- Integrated AI capabilities
- Internationalization and dark/light themes

Technical features include rate limiting, cursor-based pagination, secure authentication, and scheduled data-processing jobs.

I am happy to demonstrate the platform and discuss its architecture and implementation with recruiters, hiring managers, and engineers interested in the work.

---

## Key Accomplishments

### Engineering Tools and Process Improvements — Approximately €4M in Estimated Savings

Over an 18-month period, I independently initiated and led the development of engineering tools and process improvements.

These changes resulted in an estimated **35% reduction in labor time**, generating approximately **€4M in savings to date**, with a projected long-term impact of up to **€15M**.

### Smart Wiring Platform

I independently designed and developed a smart wiring platform comparable in concept to commercial EPLAN solutions.

The platform transformed EPLAN exports into an interactive, server-based application for cabinet assembly, providing:

- Project-based wiring guidance
- Advanced cable filtering
- Clear instructions for technicians
- Assembly workflows without the need for physical schematics

The solution was recognized by industry professionals for its completeness and practical usability.

---

## About My Public Repositories

My public repositories include technical references, smaller projects, and **ShopForge**, a larger platform currently under development.

Most of my professional codebases are covered by NDA, and TradingLenses is also private. Other projects are presented through live websites and demonstrations, so the repositories here represent only part of my work.

---

## What I Work On

- Backend and full-stack application development
- C# architecture and technical leadership
- Python data processing and analytics systems
- SQL and database design
- Multi-tenant platforms and e-commerce systems
- IoT data ingestion and utility consumption analytics
- Financial analytics software
- Engineering tools and industrial automation software

---

## Contact

If you are a recruiter, hiring manager, or engineer interested in my work, feel free to reach out.

While I cannot share most production repositories publicly, I am happy to discuss my experience and demonstrate selected private projects where appropriate.
