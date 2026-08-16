The rendering issue happens because your editor does not parse raw HTML (`<div>`, `<br>`) alongside standard Markdown headings and horizontal rules, causing broken formatting.

Here is a pure standard Markdown version—no HTML tags, no complex tables, no raw tags, and no citations. It uses clean line breaks, bold labels, and simple lists that render perfectly on GitHub, VS Code, and standard Markdown viewers.

```markdown
# Mohit Singh
**Java Backend Developer**

mohitsinghchandel785@gmail.com | [LinkedIn](https://linkedin.com/in/mohit-singh-37966720b) | [GitHub](https://github.com/mohitsingh785)

---

## Profile

Java Backend Developer specializing in designing and building scalable RESTful APIs, microservices, and high-performance backend platforms using Java 17, Spring Boot, and PostgreSQL. Experienced in optimizing production databases, refactoring core business logic, and deploying secure enterprise systems.

---

## Technical Skills

* **Languages & Core:** Core Java (17/21), RESTful APIs, Microservices Architecture
* **Frameworks:** Spring Boot, Spring MVC, Spring Data JPA, Hibernate, Spring Batch, Spring Security
* **Databases & DevOps:** PostgreSQL, MySQL, SQL Optimization, Docker, Git, Maven, Jenkins
* **Testing & Security:** JUnit, Mockito, OAuth2, JWT, Postman, SLF4J/Logback

---

## Professional Experience

### Tata Consultancy Services
**Spring Boot Developer – PG&E Energy Insights**  
*Jul 2024 – Present | Rewa, India*

* Developed and optimized RESTful APIs on a Java 17 / Spring Boot microservices platform handling energy account management, rebates, and CARE/FERA discount programs.
* Refactored CARE and FERA discount calculation logic, resolving count discrepancies across **50,000+ monthly records** and eliminating recurring business-rule defects in discount decisions.
* Replaced a legacy cron job with an automated Spring Batch pipeline for expired-discount processing, saving **15+ hours of manual month-end recovery work** per billing cycle.
* Implemented Hibernate Envers audit trails across primary account and rate tables, reducing dispute investigation times by **30%** via field-level change history tracking.
* Secured service endpoints by implementing Spring Security workflows with OAuth2/JWT role-based access control (RBAC).
* Optimized PostgreSQL/MySQL queries and created targeted indices on high-traffic endpoints to improve response times on heavy customer data queries.
* Diagnosed production issues using SLF4J/Logback analysis and collaborated with cross-functional Agile teams through SIT/UAT cycles.

### Agentinsights.live
**Android Developer – Internship**  
*Nov 2023 – Apr 2024 | Delhi, India*

* Built the core call-recording capture and background data transmission pipeline, improving audit-accuracy analytics for enterprise client workflows.

### NextGen Techno Ventures Pvt Ltd
**Java Android Developer – Internship**  
*Jul 2023 – Sep 2023 | Mumbai, India*

* Developed the Filter App’s DND engine, integrating custom call/WhatsApp blocking logic, SIM-specific rules, and cloud-synced blocklists.

---

## Projects

### TruWiz – Personalized Product Analysis Platform
*Jan 2025 – Present*

* Built a RESTful backend service using Java 21 and Spring Boot to evaluate skincare ingredients against user profile constraints (allergies/skin type).
* Designed a fallback pipeline incorporating OCR image scanning for unknown product barcodes, integrating the OpenAI API to generate dynamic safety scores and natural-language risk breakdowns.
* Created an admin review workflow for unrecognized products scanned via OCR to naturally expand the master ingredient database over time.

---

## Education

**Government Engineering College (REC), Rewa**  
Bachelor of Science in Computer Science | **CGPA: 7.76 / 10**  
*Dec 2020 – May 2024*

---

## Coding Profiles & Certifications

* **LeetCode:** [900+ Problems Solved](https://leetcode.com/mohitsinghchandel785)
* **GeeksforGeeks:** [850+ Problems Solved](https://www.geeksforgeeks.org/user/mohitsinghchandel785)
* **HackerRank:** 5 Stars in Java
* **Certifications:** Java Programming (Udemy)

```
