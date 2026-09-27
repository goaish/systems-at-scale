# systems-at-scale

# Systems at Scale

Building backend systems from scratch and scaling them from
1 user to 1 million users.

The goal isn't to add technology for the sake of technology.

The goal is to understand:

> What breaks when traffic increases, and what architectural
> decision actually fixes it?

---

## Scaling Journey

| Stage | Users | Focus |
|------|------:|-------|
| V1 | 1 | Basic architecture |
| V2 | 10 | Connection management |
| V3 | 100 | Caching |
| V4 | 1K | Horizontal scaling |
| V5 | 10K | Replication + observability |
| V6 | 100K | Distributed processing |
| V7 | 1M | Distributed architecture |

---

## Projects

### 01. URL Shortener

A URL shortening service built incrementally from a
single-user system to a distributed system.

Current stage:

**1 user**

Architecture:

Client → API → PostgreSQL

---

## Engineering Philosophy

Every optimization should answer a question.

- What is the bottleneck?
- How did we measure it?
- Why did it happen?
- What changed?
- Did the change actually improve performance?

No technology is introduced just because it is popular.

---

## Tech

- Node.js
- TypeScript
- Express
- PostgreSQL
- Redis
- Docker
- Load testing
- Distributed systems

---

## Progress

- [x] URL Shortener — 1 user
- [ ] URL Shortener — 10 users
- [ ] URL Shortener — 100 users
- [ ] URL Shortener — 1K users
- [ ] URL Shortener — 10K users
- [ ] URL Shortener — 100K users
- [ ] URL Shortener — 1M users

---

## Future Systems

- Rate Limiter
- Notification System
- Chat System
- News Feed
- File Storage System
- Job Queue
- Payment System
