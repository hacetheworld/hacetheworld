# Ajay Meena

Full-Stack Software Engineer — Backend & Event-Driven Systems · Open to Remote

I build backend systems around event streams and ledgers — the kind of work where correctness matters more than speed of shipping. Right now that means a multi-entity double-entry accounting platform; before that, signage systems, visitor automation, and internal tooling.

**Email:** majay1638@gmail.com · **LinkedIn:** https://linkedin.com/in/ajay-meena1

---

### What I work with

```
Languages     TypeScript · JavaScript · Python
Backend       Node.js · NestJS · Express.js · REST APIs · JWT/Auth
Data/Events   Kafka · Debezium (CDC) · BullMQ · Redis · MySQL · MSSQL · MongoDB · ElasticSearch
Frontend      React.js · TypeScript · HTML5 · CSS3
Cloud/DevOps  GCP · Docker · CI/CD · Git · Observability (logs/metrics/traces, RUM)
```

### Currently

Working on a multi-ledger, double-entry accounting system built on [Formance](https://www.formance.com/) — every posting has to stay balanced, attributed, and reconcilable across entities. I built the event-sync pipeline (MySQL → Debezium CDC → Kafka) that turns domain events into deterministic ledger postings, and an audit-trail subsystem for tracing every batch end to end.

### A few things I've built

- **Event-sync pipeline** — CDC-based streaming from MySQL into Kafka, driving an event engine that maps business events to ledger postings.
- **Audit-trail subsystem** — write-side event capture + read-side UI with cursor pagination, for financial traceability.
- **Digital signage platform** — designed and shipped end to end: React frontend, Express REST APIs, MSSQL schema, admin dashboards, device-communication flows. Also made the call to use React over Angular after weighing performance and maintainability.
- **Face-recognition visitor automation** — Python, OpenCV, face_recognition — cut manual form-filling by ~90%, tuned for low false positives. Used ElasticSearch for fast matching, Dockerized the delivery pipeline.
- **AI code-review bot** — watches GitHub PRs and flags SQL-injection risks, code-quality issues, and guideline mismatches. Chunk-based processing so it can handle large PRs without losing review context.

### Background

3.5 years across four roles — junior developer to owning features end-to-end. I've worked with ambiguous requirements more than once: picking an architecture during requirement-gathering, building something from a blank repo, or troubleshooting production issues alongside senior engineers before I had the experience to do it alone.

---

📫 Reach me at majay1638@gmail.com or open an issue on any of my repos.
