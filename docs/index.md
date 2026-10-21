# David Tsofin
**Senior Backend Engineer | Technical Lead | AI Systems**

Bratislava, Slovakia (EU work permit, contracting via own entity) | [tsofindavid@gmail.com](mailto:tsofindavid@gmail.com) | [LinkedIn](https://www.linkedin.com/in/tsofindavid/) | [PDF Version](https://github.com/tsofindavid/david.tsofin.com/raw/main/david-tsofin-cv.pdf)

## Summary

Senior Backend Engineer with 6+ years of experience building and operating production backend systems. Strong in Node.js, TypeScript, PostgreSQL, AWS, distributed systems, data pipelines, and API design. Hands-on experience with idempotent processing, concurrency control, database performance optimization, and production reliability. Also builds AI-powered applications and agent integrations using LLM APIs, MCP, and retrieval-based systems. Comfortable owning features end to end, from architecture and implementation to CI/CD, deployment, and production support.

## Technical Skills

- **Languages:** TypeScript, JavaScript, Go, Java, Python, C#, SQL
- **Backend:** Node.js, NestJS, Express, Spring Boot, ASP.NET Core, REST APIs, microservices, event-driven architecture, RabbitMQ
- **Databases & Data:** PostgreSQL, MySQL, MongoDB, Redis, Elasticsearch, query optimization, schema migrations, data pipelines, data consistency
- **Cloud & DevOps:** AWS Lambda, ECS, S3, RDS, Docker, Kubernetes, Terraform, GitHub Actions, CI/CD, Prometheus, Grafana, ELK
- **Distributed Systems:** Idempotency, concurrency control, request-state tracking, database locking, reliability, production debugging
- **AI Systems:** OpenAI API, Anthropic API, LLM applications, AI agents, RAG, MCP, tool calling, vector search, Qdrant, pgvector, human-in-the-loop workflows
- **Security & Integrations:** OAuth2, OIDC, SAML, access control, Salesforce APIs and metadata

## Experience

### Success Craft — Backend Engineer → Technical Lead
*Feb 2022 – Present | Remote · B2B Contract*

Hands-on backend engineer working on the architecture, implementation, deployment, and reliability of an enterprise Salesforce DevOps platform.

- Designed, implemented, and maintained backend services across an AWS-based architecture of approximately 30 microservices, taking features from technical design through production deployment.
- Implemented idempotent request processing using idempotency tokens, request-state tracking, and database-level locking where needed to prevent duplicate execution and coordinate concurrent operations.
- Designed and maintained data-processing pipelines for a Git-like change-tracking system (PostgreSQL metadata, customer data in Amazon S3), processing hundreds of gigabytes daily.
- Optimized PostgreSQL queries, investigated production performance bottlenecks, and implemented database schema changes and migrations for a large-scale enterprise platform.
- Diagnosed complex database issues, including recursive queries capable of exhausting database resources, and addressed performance and reliability risks.
- Led backend architecture and contributed hands-on to a multi-year migration of several hundred enterprise customers from a native DevOps product to a cloud platform.
- Developed and maintained public REST APIs and Salesforce integrations, including OAuth2, OIDC, and SAML authentication.
- Built an MCP integration layer over existing backend services, exposing system capabilities to AI agents through composable tools and pre-call validation.
- Improved production AI-generation workflows by analyzing whether users accepted, rejected, or modified AI-generated Salesforce test classes and other code changes, using these signals to guide improvements.
- Set up and extended GitHub Actions CI/CD pipelines across ~100 repositories, covering automated builds, testing, and deployments to AWS.
- Provided technical direction and code-level guidance across a product organization of approximately 30 people, including around 15 backend engineers, and mentored five engineers toward independent ownership.

**Stack:** Node.js, TypeScript, NestJS, PostgreSQL, MySQL, AWS Lambda, ECS, S3, RDS, RabbitMQ, Docker, Kubernetes, Terraform, GitHub Actions, Prometheus, Grafana, OpenAI API, Anthropic API, MCP.

### Independent Consulting & Product Development
*AI Automation & Backend Systems*

- **Legal knowledge base for AI agents:** Built an ingestion and semantic-search pipeline over current and historical legislation: three legal collections of ~700K chunks each (~2.1M total). Vector search over 1024-dimensional embeddings on Qdrant and pgvector with millisecond-level retrieval latency. Exposed via REST API with access control and as MCP tools for AI agents.
- **AI-powered tender document automation:** Built a pipeline that transforms 20–30-page tender requirements into submission-ready documents using client DOCX templates. AI-generated changes are marked for human review. Reduced preparation time from approximately five hours to 30 minutes per document.
- **AI sales agent for Instagram:** Independently built and shipped a production application in approximately six weeks, designed to handle up to 100K messages per day. The agent follows an account's communication style, handles routine direct messages according to user-defined scenarios, and escalates other conversations to a human.

**Stack:** Node.js, TypeScript, Go, Java, Spring Boot, React, Vue.js, PostgreSQL, Qdrant, pgvector, Telegram Bot API, LLM APIs, MCP.

### Whale Studio — Backend Engineer
*Jun 2021 – Feb 2022*

- Built real-time multiplayer backend functionality using WebSockets and Socket.IO.
- Improved performance of high-traffic e-commerce systems through Redis caching and PostgreSQL query optimization.
- Contributed to backend implementation and production troubleshooting.

**Stack:** NestJS, Node.js, TypeScript, Socket.IO, PostgreSQL, Redis.

### Alpha Orion — Full-Stack Developer
*Sep 2019 – Jun 2021*

- Developed backend services for UAV fleet management, covering fleet state, telemetry, and mission data.
- Built and tested systems spanning backend services, an Electron desktop client, and Arduino-based industrial hardware.
- Worked across implementation, integration, testing, and debugging of software-hardware workflows.

**Stack:** ASP.NET Core, C#, PostgreSQL, RabbitMQ, JavaScript, Electron.

## Education

**Slovak University of Technology in Bratislava** — BSc, Applied Informatics  
2024 – Present

**Belarusian National Technical University** — IT and Robotics  
2018 – 2020

## Languages

English — Professional working proficiency · Slovak — B1 · Russian — Native

---

*CV v0.0.2*