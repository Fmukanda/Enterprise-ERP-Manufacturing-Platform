# Enterprise-ERP-Manufacturing-Platform

```
Mobile App (React Native)
Web App (React / JS)
        ↓
API Gateway (Go)
        ↓
---------------------------------------------------
| Auth & Identity (Java + Spring Security)       |
| Accounting Engine (C# .NET)                    |
| CRM & Sales (Python FastAPI)                   |
| Inventory & MRP Engine (C / C++)               |
| E-commerce Services (Node.js)                  |
---------------------------------------------------
        ↓
PostgreSQL | Redis | Message Queue
```


| Domain               | Language                 | Reason (Real-World Use)            |
| -------------------- | ------------------------ | ---------------------------------- |
| API Gateway          | **Go**                   | High concurrency, fast routing     |
| Authentication / IAM | **Java (Spring Boot)**   | Enterprise security standards      |
| Accounting / Finance | **C# (.NET)**            | Strong typing, financial precision |
| CRM & Reporting      | **Python**               | Fast dev, analytics, exports       |
| Manufacturing (MRP)  | **C / C++**              | Performance-critical calculations  |
| E-commerce APIs      | **JavaScript (Node.js)** | Payments, webhooks                 |
| Web UI               | **JavaScript (React)**   | Enterprise dashboards              |
| Mobile App           | **React Native**         | Warehouse & sales teams            |
