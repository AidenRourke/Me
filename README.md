# Aiden Rourke
[LinkedIn](https://linkedin.com/in/aidenrourke/) | +1-613-879-3686 | [aidenrourke@gmail.com](mailto:aidenrourke@gmail.com) | [GitHub](https://github.com/AidenRourke)

---

## Summary

Senior software developer with 5 years building and scaling full-stack, microservice-based products, from a company-wide payment migration to backend performance and data-integration work. Fluent with agentic AI tools as part of everyday development.

---

## Skills

**AI & Agentic Development:** Claude Code (daily driver), LLM tool-calling, MCP (Model Context Protocol), AI agents (Mastra), chatbot integration, prompt debugging  
**Languages & Frameworks:** JavaScript (Node.js, React), TypeScript, Java, Go, Groovy, HTML/CSS, Express, Spring Boot  
**Databases & Storage:** MongoDB, MariaDB/MySQL, Elasticsearch, JDBC data warehouses (BigQuery, Snowflake, PostgreSQL)  
**Infrastructure & Tools:** Kubernetes (Docker, Helm), Git/GitHub, REST APIs, microservices, CData JDBC drivers, YourKit Profiler  
**Concepts:** Payment systems (Stripe, Zuora), 2FA, performance optimisation, data visualisation

---

## Experience

### **Klipfolio** — *Senior Software Developer*
*Ottawa, ON | June 2021 – July 2026*

- Drove core backend work in migrating the company's billing system from Zuora to Stripe: untangled Zuora dependencies woven throughout the application and reimplemented its behaviour against the Stripe API in a new subscription-management microservice.
- Took an MCP tool over the company's query infrastructure from hackday concept to full technical spike, connecting it to the product's AI chatbot to turn natural-language questions into the metrics that answer them.
- Cut a critical API's load time from up to a minute to ~10 seconds by paginating data spread across multiple microservices and reworking a front end that had assumed the full asset was loaded in browser memory.
- Designed and built an internal tool for the support team to summarise partner-account limits and usage across clients, aggregating data spread across multiple microservices via an async loading job; proposed the design and secured stakeholder approval.
- Extended the service that ran SQL against existing data connectors to also query users' own data warehouses: added JDBC connectivity, schema querying, and warehouse-specific handling in the SQL translation layer, letting users build metrics directly on their warehouse data.
- Maintained the data connectors powering curated and custom queries; diagnosed breakages across driver versions and provider-side schema changes, producing minimal repros for the vendor and remapping changed fields while keeping existing queries working.
- Configured and managed services in Klipfolio's Kubernetes cluster: building Docker images, authoring Helm charts, and deploying new microservices.

---

## Projects

### **AI Calendar Assistant**
- Built and deployed a personal calendar server (Node.js/Express), self-hosted on an always-on home machine and served privately over Tailscale.
- Integrated an AI agent (Mastra framework) that connects to a Notion database via the Notion API, and a custom iCal feed that syncs the Notion calendar with Apple Calendar.

### **Securing External JavaScript (Honours Project)**
- Built a prototype demonstrating secure integration of external JavaScript using Secure EcmaScript (SES).

---

## Education

### **Carleton University** — *Bachelor of Computer Science (Honours), Minor in Psychology*
*Ottawa, ON | September 2016 – May 2021*

- GPA: 3.8/4 | Dean's Honour List | Director of the School of Computer Science Award
