# Research Collaboration & Academic Bounty Network

A two-sided Research Information Management (RIM) platform and technical talent marketplace designed to eliminate institutional research silos and automate student-faculty project matchmaking.

## System Architecture
* **Database Layer (`/database`):** PostgreSQL 16 with automated PL/pgSQL triggers enforcing marketplace rate-limiting and relational integrity.
* **Backend API (`/backend`):** RESTful API handling Role-Based Access Control (RBAC), Jaccard similarity expertise matching, and asynchronous GitHub metric verification.
* **Frontend Client (`/frontend`):** Role-specific dashboards for grant/bounty management and interactive network graph visualization.

## Core Engineering Features
1. **Asymmetric Project Bounties:** Scoped research deliverables posted by Principal Investigators (PIs).
2. **Automated Technical Vetting:** Integration with the GitHub REST API to quantify applicant commit activity alongside verified campus organization trust badges.
3. **Database-Level Concurrency Control:** Custom PostgreSQL triggers preventing application spam under concurrent request loads.
4. **Confidential Grant Tracking:** Field-level RBAC isolating sensitive funding metrics to authorized administrative roles.

## Local Development Setup
*(Instructions to be populated in Step 2 via Docker Compose)*
