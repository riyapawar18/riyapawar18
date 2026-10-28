<h1 align="center">Riya Rajesh Pawar</h1>

<p align="center">
  <strong>Java Full Stack Developer · Backend Developer · Software Engineer</strong>
</p>

<p align="center">
  B.Tech Computer Science and Engineering student building secure, database-backed web applications with Java, Spring Boot, and React.
</p>

<p align="center">
  <a href="mailto:riyapawar054@gmail.com"><img src="https://img.shields.io/badge/Email-riyapawar054%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/riyapawar18"><img src="https://img.shields.io/badge/GitHub-riyapawar18-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
</p>

---

## About

I am a Computer Science student who enjoys the parts of software where correctness and trust matter: authentication flows, data modelling, API contracts, and encryption boundaries. I build full-stack applications with Java and Spring Boot on the backend and React on the frontend, and I document them so another developer can run the project without guessing.

I am currently looking for **Java Full Stack, Backend, or Software Engineer internship / fresher roles**.

- **Backend:** REST APIs, JWT authentication, role-based authorization, relational data modelling.
- **Frontend:** auth-aware React applications, reusable components, API integration, responsive UI.
- **Security:** OAuth 2.0, AES-256-GCM, password hashing, and post-quantum concepts (ML-KEM).
- **Working style:** clear READMEs, reproducible setup, honest documentation of limitations.

## Skills

| Area | Technologies |
| --- | --- |
| Languages | Java, C++, JavaScript, Python |
| Frontend | React.js, HTML5, CSS3, Tailwind CSS |
| Backend | Spring Boot, Spring MVC, Spring Security, REST APIs, Spring Data JPA, Hibernate, FastAPI |
| Databases | MySQL, H2 (testing), local JSON persistence |
| Security & Auth | JWT, OAuth 2.0, BCrypt, AES-256-GCM, ML-KEM concepts |
| Tools | Git, GitHub, Maven, Postman, npm, Docker |

## Featured projects

### RailAssist AI — TrainConcierge

**Problem:** a rail disruption forces a passenger to coordinate alternatives, cancellation or rebooking, a hotel, and a cab across separate services, with no single notification trail.

**What I built:** a full-stack rail assistant where passengers search trains, book and cancel seats, rebook onto alternatives, set seat-availability alerts, and add hotel or cab reservations to a journey. Admins manage trains and simulate delays or cancellations, which notify affected passengers and suggest alternatives.

**Verified implementation:**

- Spring Security with stateless JWT authentication and passenger/admin roles.
- Transactional booking, cancellation, and rebooking with seat inventory updates.
- Admin disruption simulation (`DELAY` / `CANCEL`) with passenger notifications and alternative-train suggestions.
- Seat alerts, notification read/unread state, and admin booking/stat views.
- Optional RailRadar train-data provider merged with local results.
- React 18 + Vite frontend with protected passenger and admin routes.

**Stack:** Java 21 · Spring Boot 3.3.4 · Spring Security · JWT · MySQL · React 18 · Vite · Tailwind CSS

**My contribution (Backend Developer):** authentication APIs, JWT security, database design, journey and booking flows, and railway data-provider integration.

**Scope note:** this is a rule-based prototype. Disruptions are admin-triggered, hotel/cab data is simulated, and no ML model is included.

[Repository →](https://github.com/riyapawar18/Train-Concierge)

### QuMail — Quantum Secure Email Client

**Problem:** email is usually plaintext, and security concepts such as one-time pads and post-quantum key exchange are difficult to demonstrate in a usable mail interface.

**What I built:** a secure email client that combines a real Gmail integration with a self-contained encryption demo, so the app can be evaluated without Google credentials.

**Verified implementation:**

- Server-side Google OAuth 2.0 flow; tokens remain server-side and never reach the browser.
- Gmail inbox, message detail, read/unread, trash, attachment download, and send flows.
- QuMail encryption levels L1–L4 with AES-256-GCM for authenticated paths.
- Guest demo with isolated in-memory sessions and real per-session AES-256-GCM encryption.
- Mock DigiLocker vault with synthetic documents and an "Attach to Email" flow.
- Sanitized HTML email rendering and validated, size-capped attachment routes.

**Stack:** React 18 · Python · FastAPI · Gmail API · OAuth 2.0 · AES-256-GCM · ML-KEM (optional)

**My contribution (Frontend & Secure Email Module):** email send/receive UI, attachment handling, Gmail integration, and the encryption layer.

**Recognition:** selected as a **Top 5 finalist at Smart India Hackathon 2025** for the ISRO problem statement (300+ ideas).

**Scope note:** guest mail and the DigiLocker vault are demonstrations; real Gmail use requires the viewer's own Google OAuth client. ML-KEM is used only when the optional `quantcrypt` dependency is installed.

[Repository →](https://github.com/riyapawar18/QuMail)

## More repositories

| Repository | What it contains |
| --- | --- |
| [DSA-LeetCode](https://github.com/riyapawar18/DSA-LeetCode) | 89 published C++ solutions with notes, organized by problem (part of 200+ problems solved) |
| [java-resume-management-system](https://github.com/riyapawar18/java-resume-management-system) | Spring Boot, MySQL, JPA/Hibernate, Thymeleaf resume management app with CRUD REST APIs |
| [Invoice-Chain](https://github.com/riyapawar18/Invoice-Chain) | React invoice-financing prototype with wallet connection, invoice minting, and escrow-status UI ([live demo](https://invoice-chain-rosy.vercel.app)) |
| [Python](https://github.com/riyapawar18/Python) | Python and machine-learning practice notebooks |

## GitHub activity

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=riyapawar18&show_icons=true&hide_rank=true&include_all_commits=true&theme=default" alt="Riya's GitHub statistics">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=riyapawar18&layout=compact&langs_count=8&theme=default" alt="Most-used languages">
</p>

<p align="center">
  <img src="https://ghchart.rshah.org/2f81f7/riyapawar18" alt="Riya's GitHub contribution chart">
</p>

<sub>Statistics are generated dynamically by third-party open-source services and may be temporarily unavailable.</sub>

## Problem solving

- **200+ LeetCode problems solved in C++** — 89 published solutions in [DSA-LeetCode](https://github.com/riyapawar18/DSA-LeetCode) spanning arrays, strings, linked lists, stacks, binary trees/BSTs, sliding window, and binary search.

## Achievements and leadership

- **Smart India Hackathon 2025 — Top 5 finalist** for the ISRO problem statement (300+ ideas) with QuMail.
- **Top 3 final-year diploma topper** — 87.66% in Computer Science and Engineering.
- **Computer Science Association:** Student Coordinator (2022–2023), Vice President (2023–2024).
- **Training & Placement Cell:** Student Representative (2025–2026).

## Experience

**Java Full Stack Developer Intern — ITnium Technologies (2024)**

Worked on secure web application features and backend services, and integrated REST APIs into existing application flows.

## Education

| Qualification | Institution | Year | Result |
| --- | --- | --- | --- |
| B.Tech, Computer Science and Engineering | Annasaheb Dange College of Engineering and Technology | 2025–2027 | CGPA 8.42 |
| Diploma, Computer Science and Engineering | Sharad Institute of Technology Polytechnic, Ichalkaranji | 2021–2024 | 87.66% |

**Certifications:** Python for Machine Learning · Java Full Stack Development · C++

## Contact

I am open to **Java Full Stack, Backend, and Software Engineer internship / fresher opportunities**.

- **Email:** [riyapawar054@gmail.com](mailto:riyapawar054@gmail.com)
- **GitHub:** [github.com/riyapawar18](https://github.com/riyapawar18)

The best way to evaluate my work is to open a repository, follow its setup section, and read the limitations alongside the features.
