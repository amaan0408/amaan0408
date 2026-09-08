<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=2E9EF7&center=true&vCenter=true&width=700&lines=Backend+Engineer+%7C+Open+Source+Contributor;Java+%7C+Spring+Boot+%7C+Distributed+Systems;Shipped+to+Keycloak.+Always+building." alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amaan-hawaldar-36602b286/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amaan0408)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/amaan0408)

</div>

---

## 👋 Who I Am

Java backend engineer building **reliable, secure systems** that scale. I live in the intersection of clean architecture, real-world constraints, and distributed systems.

**Currently:** Contributing to major open-source projects while strengthening depth in backend engineering.

**Previously:** Technical Consultant intern at Quorum Software. Worked on enterprise Java systems, authentication, caching, and real-world data handling.

**Next:** Keycloak and identity/access systems. Long-term goal: Red Hat or similar product company building the infrastructure layer.

---

## 🚀 Open Source: Keycloak

### [Keycloak PR #51912 — MERGED](https://github.com/keycloak/keycloak/pull/51912)

Fixed policy evaluation for `TOKEN_EXCHANGE_REQUEST` and `JWT_AUTHORIZATION_GRANT` in Keycloak's lightweight token executor.

**The Problem:** Token exchange and JWT authorization grants were ignoring the `use-lightweight-access-token` policy — a subtle but critical bug in an identity platform used by thousands.

**The Solution:** Added two case labels to `UseLightweightAccessTokenExecutor` to ensure both grant types properly evaluate policies.

**The Impact:** 
- ✅ Merged into `keycloak:main` by **@mposolda** (Red Hat maintainer)
- ✅ 93/94 CI checks passed
- ✅ Now in production Keycloak used globally
- ✅ Regression test ensures it never breaks again

**What This Taught Me:** Reading unfamiliar codebases, test-driven debugging, CI/CD troubleshooting, and how to collaborate with maintainers on complex systems.

---

## 🛠 What I Build

### CoreVector AI — Vector Search Engine from Scratch

**[Repository](https://github.com/amaan0408/CoreVector-AI)**

Built a production-grade vector search engine entirely in Java and shipped it behind a secured REST API.

**Technical depth:**
- Implemented **HNSW, KD-Tree, and Brute Force** search algorithms behind Strategy pattern
- Integrated **RAG pipeline** with Ollama + local LLM
- **JWT auth + role-based access control** + multi-tenant isolation
- 12 REST endpoints, full CRUD for vectors and documents

**Why this matters:** Proves I can implement algorithms from scratch, secure APIs, and integrate modern ML tooling with traditional Java backends.

---

### Offline UPI Mesh Payment System

**[Repository](https://github.com/amaan0408/UPI_Without_Internet)**

Designed an idempotent payment processing backend that works over mesh routing (no internet guaranteed).

**The hard problems I solved:**
- **Idempotency at scale:** SHA-256 fingerprinting + Redis atomic operations + TTL-based cleanup
- **Encryption:** AES/RSA hybrid for payment data
- **Concurrency:** Multi-threaded transaction safety under stress
- Verified with concurrent load testing

**Why this matters:** Real-world systems need idempotency, encryption, and concurrency correctness. Most people talk about this. I built it.

---

### Enterprise Workforce API

**[Repository](https://github.com/amaan0408/Enterprise_Workforce_API)**

RESTful backend for employee/department management with proper security layers.

- JWT authentication + role-based authorization
- JPA entity relationships, JPQL queries, pagination
- DTOs, validation, global exception handling
- BCrypt password hashing

**Why this matters:** This is the foundation. Clean architecture, security basics, and API design done right.

---

## 💡 Technical Stack

### Core Languages
`Java` · `SQL` · `C++` · `C`

### Backend & Frameworks
`Spring Boot` · `Spring Security` · `Spring Data JPA` · `Hibernate` · `REST APIs` · `JDBC`

### Advanced Java
`Concurrency & Multithreading` · `Streams & Lambdas` · `Collections Framework` · `Dependency Injection` · `Exception Handling` · `OOP Design Patterns`

### Security & Cryptography
`JWT` · `RBAC` · `BCrypt` · `AES/RSA` · `SHA-256` · `Authentication & Authorization`

### Databases
`MySQL` · `PostgreSQL` · `Oracle` · `H2` · `JPQL` · `Complex Queries & Indexing`

### Distributed Systems & Infrastructure
`Redis` (caching, atomic ops, idempotency) · `TTL & Expiration` · `Load Balancing` · `Docker` · `Client-Server Architecture`

### Tools & Workflow
`Git` · `Maven` · `GitHub` · `Postman` · `IntelliJ IDEA` · `Jira`

---

## 📊 Algorithm & Problem Solving

[![LeetCode](https://img.shields.io/badge/LeetCode-amaan0408-FFA116?style=flat&logo=leetcode&logoColor=white)](https://leetcode.com/amaan0408)

Practicing DSA in Java:
- Arrays, strings, hashing, two pointers, sliding window
- Linked lists, stacks, queues, trees, graphs
- Sorting, searching

Building problem-solving skills.

---

## 📈 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=amaan0408&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=amaan0408&layout=compact&theme=tokyonight&hide_border=true" />

</div>

---

<div align="center">

**Java · Spring Boot · Distributed Systems · Open Source**

</div>
