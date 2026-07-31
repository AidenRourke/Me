# Aiden Rourke
[LinkedIn](https://linkedin.com/in/aidenrourke/) | +1-613-879-3686 | [aidenrourke@gmail.com](mailto:aidenrourke@gmail.com) | [GitHub](https://github.com/AidenRourke)
---
## Summary
Senior full-stack developer with 5+ years on a SaaS business intelligence platform: billing and subscriptions, backend services, and the AI agent tooling built on top.
---
## Skills
**AI & Agentic Development:** Claude Code (daily driver), LLM tool-calling, MCP (Model Context Protocol), AI agents (Mastra), prompt debugging  
**Languages & Frameworks:** TypeScript, JavaScript, Java, Go, Groovy, Node.js, Grails, Spring Boot, Express, React, Kubernetes (Docker, Helm), HTML/CSS  
**Concepts:** Microservice architecture, REST API design, authentication and authorization (MFA/TOTP, OAuth), relational and non-relational databases, query optimization, legacy system migration
---
## Experience
### **Klipfolio** — *Senior Software Developer*
*Ottawa, ON | June 2021 – July 2026*
- Took an MCP tool over the company's query infrastructure from hackday concept to working proof of concept, connecting it to the product's AI chatbot to turn natural-language questions into metrics.
- Led backend work migrating billing for ~1,200 paying customers from Zuora to Stripe, untangling Zuora dependencies across the application and reimplementing them in a new subscription-management microservice.
- Cut the metric library page's load time from ~60s to ~10s by replacing in-memory filtering and pagination with server-side equivalents at full feature parity.
- Enabled customers to define metrics in their own data warehouses, generating warehouse-specific SQL over JDBC and maintaining the connectors behind it through driver changes.
- Implemented MFA (TOTP, emailed codes, recovery codes, rate limiting) in a 15-year-old login flow, mapping the existing authentication path to place the check where it could not be bypassed.
- Proposed and shipped an internal tool giving support a single view of partner-account limits and usage, replacing a legacy tool that read from one database after usage data had spread across microservices.
---
## Projects
### **[AI Calendar Assistant](https://github.com/AidenRourke/notion-calendar)**
- Built a self-hosted, multi-user AI chat assistant (Node.js/Express, privately networked via Tailscale): a Mastra tool-calling agent with per-user persistent conversation memory (LibSQL), fronted by a streaming React (assistant-ui) UI.
### **[Securing External JavaScript](https://github.com/AidenRourke/4905-honours-project) (Honours Project)**
- Prototyped secure integration of external JavaScript using Secure EcmaScript (SES).
---
## Education
### **Carleton University** — *Bachelor of Computer Science (Honours), Minor in Psychology*
*Ottawa, ON | September 2016 – May 2021*
- GPA: 3.8/4 | Dean's Honour List | Director of the School of Computer Science Award
