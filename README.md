# Ahmed Mohamed Omar

**Backend Developer (Backend & DevOps)** based in Cairo, Egypt. I build backend systems, ship them to Kubernetes, and care about the whole path from API design to a running deployment. Currently working on a multi-tenant app-hosting platform as a freelance Backend & DevOps Engineer.

---

## About me

I am a backend developer with an Electronics & Communication Engineering background, so I think about systems end to end: from REST APIs and database design all the way to Helm releases, container networking, and edge firmware. I have shipped production work in Node.js, NestJS, Express, FastAPI, and Python, and I have authored Helm charts, a NestJS Kubernetes orchestrator, and a Next.js control panel for the platform I am building right now.

What I enjoy most is **engineering breadth with depth, not checklists**. Every area on this profile is something I have built and shipped, from queue workers to a LiveKit-based video conferencing app, from a CPU-friendly faster-whisper transcription service to an STM32 FreeRTOS sensor node.

I work remotely, write clean documented code, and prefer to own a feature from spec to production.

---

## What I work on

- **Backend.** Node.js, NestJS, Express, FastAPI, REST APIs, WebSockets, Redis caching, BullMQ and Celery queues, PostgreSQL, MongoDB, JWT and OAuth flows.
- **DevOps & Kubernetes.** Docker, Kubernetes, Helm chart authoring, Kubernetes Gateway API, Traefik, GitHub Actions CI/CD, Nginx, self-hosted runners.
- **Full-stack.** Next.js (App Router) for React frontends, API routes, and containerized deployments, plus TypeScript, Tailwind, and a Next.js control panel for the platform I run.
- **AI integration.** Arabic-dialect voice agent design, RAG-aware microservices, agent-authorization gateways, LiveKit WebRTC, faster-whisper transcription on CPU.
- **Embedded and IoT (ECE background).** STM32, ESP32, FreeRTOS, UART, MQTT, Mosquitto, custom firmware without ESPHome, Proteus simulation.

---

## Currently

- **Freelance Backend & DevOps Engineer (Sep 2026 – Present).** Building a multi-tenant Odoo 19 app-hosting platform on Kubernetes end to end. Helm charts I author, a NestJS control plane that automates tenant lifecycle with server-side apply and a BullMQ reconcile queue, a Next.js control-panel frontend, and the Odoo application code that ships inside the tenant image. Repositories stay private.
- Open to **Backend**, **DevOps / Kubernetes**, **Next.js / full-stack**, and **AI integration** roles, remote or hybrid from Cairo.

---

## Tech stack

**Languages:** TypeScript, JavaScript, Python, SQL, Java, C, C++
**Backend and APIs:** Node.js, NestJS, Express, FastAPI, Spring Boot, REST APIs, WebSocket, Socket.IO, JWT, OAuth (Google)
**DevOps and Kubernetes:** Docker, Docker Compose, Kubernetes, Helm, Gateway API, Traefik, GitHub Actions, Nginx, Let's Encrypt
**Data and messaging:** PostgreSQL, MongoDB, Redis, BullMQ, Celery, MariaDB, SQLite, Mongoose, Sequelize, Prisma, TypeORM
**Full-stack:** Next.js (App Router), React 18/19, Tailwind, react-hook-form, Zod, Vitest, Playwright
**AI and realtime:** LiveKit, LiveKit Components, faster-whisper (CTranslate2), Edge-TTS, Groq STT, Gemini Live API, Qdrant, Deepgram
**Embedded and IoT:** STM32 (F103C8), ESP32, ATmega32, FreeRTOS, UART, MQTT, Arduino framework, STM32CubeMX, Proteus
**Tools:** Linux, Git, Postman, Swagger / OpenAPI, Datadog, SeaweedFS, MinIO, GHCR

---

## Featured projects

### Backend and APIs

- **[Call Campaign Simulator](https://github.com/AhmedMohamedomar74/ollimiTask)** (Apr 2026). Concurrent outbound call campaign engine in TypeScript. Timezone-aware scheduling windows, configurable max concurrent calls, daily-minute caps, retry-with-delay, and a clean `Campaign` / `IClock` separation for full testability.
- **[E-Share Book Platform](https://github.com/AhmedMohamedomar74/Eshare-Books)**. Real-time collaborative book sharing. Node.js, Express, MongoDB, Socket.IO, JWT plus Google OAuth, Nodemailer notifications, full CRUD.
- **[E-Commerce REST API](https://github.com/AhmedMohamedomar74/ITI-NodeJS-Ecommerce)**. Production-ready e-commerce backend. Express, MongoDB, Mongoose, Multer uploads, Nodemailer, JWT auth, Paymob payment integration.
- **[Saraha Anonymous Messaging App](https://github.com/AhmedMohamedomar74/Saraha-App)** (Aug 2025). Anonymous message delivery API. Express, MongoDB, JWT, bcrypt, modular MVC structure.
- **[Blog API](https://github.com/AhmedMohamedomar74/Blog-API-Project)**. RESTful blog backend. Express, PostgreSQL, Sequelize, relational data modeling.
- **[Demo](https://github.com/AhmedMohamedomar74/Demo)**. Express 5 + Socket.IO + MongoDB app skeleton.

### DevOps and Kubernetes (private, ongoing freelance work)

- **Odoo Tenant Factory** (private). One Helm release = one isolated tenant namespace on Kubernetes. Odoo 19, PostgreSQL 17, StatefulSets, PVCs, Secrets, ConfigMaps, Gateway API with Traefik, custom Odoo addons for first-boot company profile and per-business-type module selection.
- **Odoo Tenant Orchestrator** (private). NestJS control plane that automates the full tenant lifecycle (create, ready, suspend, resume, delete). `@kubernetes/client-node` with server-side apply, BullMQ and Redis reconcile workers, SSE status stream, JWT, Swagger / OpenAPI 3.1, plan-based sizing, server-generated passwords shown once.
- **Next.js Control Panel** (private). Companion UI for the orchestrator. Next.js 15 App Router, React 19, react-hook-form, Zod, Jest, Playwright, accessibility scans. Live SSE-driven phase timeline, plan selection, copyable one-time password reveal.

### Full-stack and realtime

- **Task Board** (private). Full-stack team task-management app. Express 5, Prisma 7, Zod 4, PostgreSQL 16, Next.js (App Router) frontend, 27 automated tests with Vitest and Supertest, RBAC with membership-scoped 404s that never leak resource existence, Swagger docs, ERD, and a documented architecture decision on admin-only project creation.
- **LiveKit Meeting App** (private, repo not yet published). Next.js 15 + LiveKit Components video conferencing app. AI noise cancellation (Krisp), Datadog browser monitoring, 5-service Docker Compose (LiveKit SFU, Redis, LiveKit Egress, MinIO, Next.js), room composite recording to S3-compatible storage, moderation panel with waiting room and webhook-driven participant cleanup, Deepgram transcription for live captions.

### Frappe LMS and deployment

- **[Simple_Lms](https://github.com/AhmedMohamedomar74/Simple_Lms)**. Customized Frappe LMS in production at `dev.scolair.site`. Python, Frappe v16/v17, Vue.js, MariaDB, Redis, Docker, GitHub Actions, GHCR. Custom modules for quizzes, question bank, homework grading, private lesson media, and an auto-transcription pipeline that ships lesson audio to a faster-whisper service over a shared Docker network. Self-hosted runner, encrypted env transfer, custom `easy-install.py` for one-command deploys.
- **Frappe Docker Infrastructure**. Custom deployment automation around Frappe Docker official images. Traefik reverse proxy, Let's Encrypt SSL, custom GitHub Actions pipeline that builds and pushes a custom image to GHCR.

### AI and transcription

- **[Transcription Faster-Whisper Service](https://github.com/AhmedMohamedomar74/transcription-faster-whisper-service)** (Jun 2026). Async audio transcription microservice. FastAPI, faster-whisper with CTranslate2 on CPU int8, Celery + Redis workers, MongoDB persistence, SeaweedFS object storage, Docker Compose. Per-request model size, audio chunking for long files, query and comparison endpoints. v2 added S3 storage, streaming, and a cross-service integration with the Frappe LMS.
- **Arabic AI Voice Call Center** (demo, private). Arabic-dialect AI call center demo. FastAPI, LiveKit, Gemini Live API, Groq STT, Edge-TTS, Qdrant, RAG knowledge-base layer integrated with Odoo and Frappe Helpdesk, LiveKit-native voice-activity detection for call latency. Contabo VPS, Docker, Nginx.

### Java / Spring Boot

- **[Patient Management Service](https://github.com/AhmedMohamedomar74/patient-management-spring-boot-)** (Jun 2026). RESTful microservice with Spring Boot 4, Spring Data JPA, Hibernate, layered architecture, DTOs and mappers, global exception handler, dual DB profiles (H2 dev, PostgreSQL prod), multi-stage Docker build, non-root container user.
- **[Sprint-Boot Tutorial](https://github.com/AhmedMohamedomar74/Sprint-Boot)** (Jun 2026). Spring Boot 4 + JPA + PostgreSQL + Docker Compose. Amigoscode tutorial project.

### Embedded and IoT

- **[STM32 JSON Node System](https://github.com/AhmedMohamedomar74/STM32-JSON-Nodes)** (Dec 2024 – Feb 2025). Embedded IoT system on STM32F103C8 with FreeRTOS, cJSON, UART, LM35 + LDR + relay, Proteus simulation. JSON commands (`ENA`, `DIS`, `ACT`, `STA`, `DUR`) drive each node by ID.
- **[HomeAssistant IoT System](https://github.com/AhmedMohamedomar74/HomeAssistant)** (Nov 2024). Real-time home monitoring on ESP32 with custom MQTT firmware (no ESPHome), Mosquitto broker, Home Assistant gauge and toggle.
- **[FreeRTOS on ATmega32](https://github.com/AhmedMohamedomar74/FreeRtos_Application_Atmega32)** (Oct – Dec 2024). FreeRTOS port to ATmega32.
- **[FreeRTOS on ATmega32 (earlier)](https://github.com/AhmedMohamedomar74/FreeRTOS-on-ATmega32)** (Mar 2024).
- **[Solar Panel Tracking System](https://github.com/AhmedMohamedomar74/Solar-panel-tracking)** (Apr – May 2024). Python orientation tracker.
- **[Wave Generator](https://github.com/AhmedMohamedomar74/Wave-Generator)** (Apr 2024). Embedded C signal / waveform generator.
- **[SmartHome Project](https://github.com/AhmedMohamedomar74/SmartHome_Project)** (Jun 2023). Early smart-home embedded project.
- **[IOT Freelance Work](https://github.com/AhmedMohamedomar74/IOT_FreeLanceError)** (May 2025). IoT debugging / error-logging helper with macro-based logger for embedded devices.
- **[Software Debugger](https://github.com/AhmedMohamedomar74/Software-Debugger)** (Mar 2024). C.
- **[ITI Graduation Project (Embedded)](https://github.com/AhmedMohamedomar74/ITI-graduation-project)** (Sep 2023). C.

### Learning

- **[NestJS Lab](https://github.com/AhmedMohamedomar74/nest-lab1)** (Oct 2025). NestJS fundamentals: decorators, modules, controllers, providers.
- **[Embedded Linux Tasks](https://github.com/AhmedMohamedomar74/Embedded-Linux)** (Aug 2024). Tasks from the Embedded Linux diploma under Hazem Khaled.
- **[ITI E-Commerce Frontend](https://github.com/AhmedMohamedomar74/ITI-E-Commerce-js)** (Jul – Aug 2025). Vanilla JS e-commerce.
- **[Movie App](https://github.com/AhmedMohamedomar74/Movie-App)** (Sep 2025). JS movie browser.
- **[Snake Game](https://github.com/AhmedMohamedomar74/Snake_Game)** (Nov 2024). Terminal snake in C.
- **[Portfolio Website](https://github.com/AhmedMohamedomar74/portfolio)** (Sep 2025).

---

## Production work at TelNova (Nov 2025 – Sep 2026)

- **Multi-tenant SaaS platform.** Docker Compose per tenant, per-subdomain Nginx routing, automated Let's Encrypt SSL, selective CI/CD. ~80% deployment time reduction and zero manual SSH releases.
- **MQTT PPE detection microservice.** Python service that subscribes to Frigate computer-vision detections over MQTT and fires automated alerts on PPE violations in camera feeds.
- **Arabic AI Voice Call Center** (demo, see above for the design contributions).
- The platform and the AI voice demo were the core backend and AI integration work during the role.

---

## Education and languages

- **B.Sc. Electronics & Communication Engineering.**
- **Arabic** (native), **English** (professional).

---

## Connect

- LinkedIn: [linkedin.com/in/ahmed-omar74](https://www.linkedin.com/in/ahmed-omar74)
- Email: ahmedmohamedomar74@gmail.com
- GitHub: [@AhmedMohamedomar74](https://github.com/AhmedMohamedomar74)

Happy to talk about backend architecture, Kubernetes platforms, Next.js full-stack, AI voice systems, or anything in between.
