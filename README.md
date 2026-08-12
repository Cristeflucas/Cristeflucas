# Cristef Azevedo
**Full-Stack Developer · Backend Engineering · Django · .NET · Mobile**

Information Systems student based in Natal, RN, Brazil.

[LinkedIn](https://www.linkedin.com/in/cristef-lucas-silva-de-azevedo-888633246/) · [Email](mailto:cristeflucas@gmail.com)

## About Me

I'm an Information Systems student at Universidade Potiguar (UNP), expected to graduate at the end of 2026, and a Full-Stack Developer working professionally with Django.

My main interests are backend engineering, REST API design and full-stack development across web and mobile. At Intesoftware, I build and maintain the Django REST APIs and React Native frontend for a production application, backed by PostgreSQL and containerized with Docker.

Outside of work, I explore the .NET ecosystem through personal projects — applying Clean Architecture, JWT authentication and payment integrations — as well as smaller projects to practice object-oriented design and API development in C#.

I'm currently open to backend, full-stack and junior software engineering opportunities in Natal/RN or remote.

## Featured Projects

### MultRH API
Backend for a job-listing management platform for an HR consulting company, with paid-subscription access control: users with an active subscription can generate a PDF referral letter for job listings, while regular users only get view access. Subscriptions are activated automatically after a real payment via Mercado Pago.

Engineering highlights:
- Clean Architecture across four projects (Domain, Application, Infrastructure, Api) with one-way dependencies
- ASP.NET Core Identity + JWT authentication, with account lockout after failed login attempts
- Role- and subscription-based authorization via claims computed dynamically at login
- Real payment processing with Mercado Pago (Transparent Checkout) and HMAC-validated webhooks for automatic subscription activation
- Rate limiting on auth endpoints, global exception handling (ProblemDetails) and structured logging with Serilog
- Automated tests with xUnit; dedicated least-privilege database user

`.NET 8` `ASP.NET Core` `Entity Framework Core` `MySQL` `JWT` `AutoMapper` `FluentValidation` `QuestPDF` `Serilog` `xUnit` `Mercado Pago SDK`

[Repository](https://github.com/Cristeflucas/MultRHAPI)

### Doutor Fácil — Production App (Intesoftware)
Full-stack development of a mobile application in production, covering both the Django backend and the React Native frontend.

Engineering highlights:
- REST APIs built with Django and Django REST Framework
- Mobile app interface implemented in React Native
- PostgreSQL database design and maintenance
- Services containerized with Docker for a consistent development and deployment environment
- Integration between backend and mobile client, including authentication and data synchronization

`Django` `Django REST Framework` `React Native` `PostgreSQL` `Docker`

*Private/professional project — not publicly available.*

### MULTRH_DJANGO
Personal Django project exploring the same domain as MultRH API — job listings and hiring — with user accounts and job postings, built to compare Django's approach to backend architecture against ASP.NET Core.

`Django` `Python`

[Repository](https://github.com/Cristeflucas/MULTRH_DJANGO)

## Additional / Learning Projects

- **jogoXadrez** — Console-based chess game in C#, built to practice object-oriented design (encapsulation, inheritance, polymorphism) and game-state modelling.
- **APICatalogo** — ASP.NET Core Web API for product/category catalog management, practicing REST conventions, EF Core and layered architecture.
- **ByteBankIO** & **Screen-Sound-04** — C# practice projects covering file I/O, LINQ and API consumption.
- **UsersApi** & **DataManipulation** — Smaller C# API and data-handling exercises.

## Technical Toolkit

| Area | Technologies |
|---|---|
| Backend & APIs | Python, Django, Django REST Framework, C#, ASP.NET Core, REST, Swagger/OpenAPI |
| Architecture | Clean Architecture, JWT / RBAC, REST API Design |
| Mobile | React Native |
| Data & Persistence | PostgreSQL, MySQL, SQL Server, Entity Framework Core |
| Engineering Tools | Git, GitHub, Docker, Docker Compose, Postman, Swagger, Serilog |
| Payments | Mercado Pago (Transparent Checkout, Webhooks) |

## Education

**Bachelor's Degree in Information Systems**
Universidade Potiguar (UNP) · 2023 – 2026 (expected)

## Professional Experience

**Full-Stack Developer — Intesoftware**
Natal, RN, Brazil · July 2025 – Present

Full-stack development of the Doutor Fácil project: Django REST APIs on the backend and the React Native mobile app frontend, with a PostgreSQL database and Docker-based deployment.

## Engineering Principles

I value:
- Clear and maintainable architecture
- Explicit functional and quality requirements
- Reliable, testable and secure code
- Well-documented APIs
- Continuous learning across different backend ecosystems

## Contact

The best ways to reach me are through [LinkedIn](https://www.linkedin.com/in/cristef-lucas-silva-de-azevedo-888633246/) or [email](mailto:cristeflucas@gmail.com).
