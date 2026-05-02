# U-bike IPBeja — Management Platform

**Course:** Software Engineering 2025/2026  
**Institution:** Instituto Politécnico de Beja — School of Technology and Management  
**Degree:** Bachelor's in Computer Engineering  
**Author:** Soufiane Achouch — Student No. 28638  
**Professors:** Isabel Sofia Brito | Tierri Fernando de Coito Ferreira  

---

## Project Overview

A management platform for the **U-bike IPBeja** bicycle sharing system, covering:

- User registration and authentication
- Bicycle fleet management and reservations
- Trip recording with health and energy indicators
- Maintenance tracking, notifications, and reports

---

## Development Model

**Incremental Development Model** — each increment follows:  
`Analysis → Design → Implementation → Validation`

| Increment | Scope | Features |
|-----------|-------|----------|
| 1 | Users & Authentication | Registration, login, user management |
| 2 | Fleet & Reservations | Add bicycles, availability, make/cancel reservations |
| 3 | Trip Recording & Indicators | Check-in/out, distance, calories, CO2 saved, history |
| 4 | Maintenance, Notifications & Reports | Fault reports, maintenance logs, alerts, fleet reports |

---

## Repository Structure

```
ubike-ipbeja/
├── docs/
│   ├── analysis/          # Requirements, stakeholders, use case specs
│   ├── design/            # Architecture, patterns, pseudocode
│   └── reports/           # Development plan and final report
├── diagrams/
│   ├── use-case/          # Use case diagrams (.vpp / exported images)
│   ├── class/             # Class diagrams
│   ├── sequence/          # Sequence diagrams
│   ├── activity/          # Activity diagrams
│   └── state/             # State diagrams
├── src/
│   ├── auth/              # Increment 1 — Authentication module
│   ├── fleet/             # Increment 2 — Fleet management
│   ├── reservations/      # Increment 2 — Reservations module
│   ├── trips/             # Increment 3 — Trip recording & indicators
│   └── maintenance/       # Increment 4 — Maintenance & notifications
├── tests/                 # Test cases per increment
└── README.md
```

---

## Schedule

| Activity | Deadline |
|----------|----------|
| Development Plan | 30 Apr 2026 |
| Research & stakeholder analysis | 5 May 2026 |
| Functional & non-functional requirements | 8 May 2026 |
| Use case diagram + specifications | 12 May 2026 |
| Class diagram | 18 May 2026 |
| Sequence diagrams | 22 May 2026 |
| Activity + state diagrams | 25 May 2026 |
| Architectural & design patterns | 28 May 2026 |
| Final report | Jun 2026 |
| Submission + defence | TBC |

---

## CASE Tools

- **Visual Paradigm** — UML diagrams (use case, class, sequence, activity, state)
- **GitHub** — version control and project file management
- **Microsoft Word** — technical report (IPBeja formatting norms)

---

## Commit Convention

```
[INCREMENT] short description

Examples:
[INC1] add user registration logic
[DOCS] update use case specifications
[DESIGN] add class diagram v1
[FIX] correct reservation cancellation flow
```
