# 🏦 United Banks of Serbia (UBS)

## 🚀 Introduction

**United Banks of Serbia (UBS)** is a centralized **inter-bank communication and collaboration platform** designed to modernize how banks across Serbia exchange and process information.
It allows banks to **securely share loan data, transfer loan applications, manage inter-bank requests**, and communicate directly — all through a unified, high-security environment.

Our goal was to replace slow, manual, and error-prone email-based communication with a **real-time, secure, and auditable** system that meets the strict standards of the financial sector.

---

## 🧠 Technologies Used

| Layer        | Stack / Tools                                                      | Description                                                                                      |
| ------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| **Frontend** | **Angular 17**, **Angular Material**, **NgRx**, **RxJS**, **SCSS** | Built a modular, reactive frontend with a state-driven architecture for clarity and scalability. |
| **Backend**  | **Java (Spring Boot)**                                             | Provided APIs, security layers, and data processing for all inter-bank operations.               |
| **Database** | **MySQL**                                                          | Managed structured data for users, transactions, and loan records.                               |
| **Cloud**    | **AWS (EC2, S3, RDS, IAM)**                                        | Hosted the application and database infrastructure with strict access control policies.          |
| **Security** | **JWT**, **CORS**, **CSRF**, **Role-based guards**, **Encryption** | Ensured high-level compliance and protection for sensitive financial data.                       |

---

## 💻 My Role & Contributions

I joined the UBS project as the **first Frontend Developer**, initially working solo to build the foundation of the application.
I **architected the Angular codebase**, established module structures, and set up **NgRx** to manage global state consistently across complex features.
As more developers joined, the established architecture became the standard that ensured stability, scalability, and maintainability of the entire codebase.

Key contributions:

* Designed the **Angular app architecture** and shared component library used across all modules.
* Implemented **NgRx for state management**, ensuring predictable app behavior, easy debugging, and clear separation between UI and business logic.
* Integrated **Angular Material** with a custom theme to align with UBS’s branding.
* Collaborated with backend engineers to define **secure data contracts**, ensuring consistency between frontend and backend.
* Led the **security integration** (JWT handling, guards, interceptors) and **performance optimization** of the UI layer.
* Mentored new developers joining the project on structure, best practices, and NgRx patterns.

---

## 🧩 What We Built

* **Bank-to-Bank Communication System** – Enables encrypted inter-bank communication within a controlled ecosystem.
* **Loan Transfer Workflow** – Supports real-time loan transfers with detailed audit trails and approval flows.
* **Secure Messaging & Request System** – Built a reliable communication channel for document exchange and inquiries.
* **Administrative Dashboard** – Manages user roles, system configurations, and inter-bank access policies.
* **Real-time Notifications & Audit Logs** – Provided full traceability and transparency for all operations.

---

## 🔐 Security & Performance Challenges (and How I Solved Them)

One of the most complex challenges was maintaining **data security and isolation** across different financial institutions — while still enabling communication and shared workflows.
To achieve this, I implemented a **multi-layered security architecture** that included:

* **NgRx state isolation** per bank session to prevent data leakage between institutions.
* **JWT-based authentication and refresh token logic**, integrated with a global Angular interceptor.
* **End-to-end encryption (E2EE)** in collaboration with backend developers for sensitive payloads.
* **CORS, CSRF, and strict role-based access control (RBAC)** to secure all endpoints.
* **Performance tuning** with lazy-loaded modules, OnPush change detection, and selective store updates — reducing UI latency by nearly **45%**.

These improvements transformed the app into a **secure, stable, and high-performing** banking platform capable of scaling across 30+ banks.

---

## 🧠 Notable Algorithms / Implementations

* **Loan Matching Engine**
  Developed a rule-based system that automatically matches compatible loan offers between banks based on parameters like rate, credit rating, and term length.
  Combined **NgRx selectors** and **RxJS streams** to synchronize filtering, sorting, and API calls — improving responsiveness by **~60%**.

* **Dynamic Access Policy Engine**
  Created a frontend configuration layer that lets admins dynamically manage access rules (without redeploying the app) using NgRx entity adapters and effect streams for real-time propagation.

---

## 🏁 Outcome

The **UBS platform** now connects **30+ major banks across Serbia**, enabling instant, secure loan transfers and direct inter-bank collaboration.
It significantly reduced processing time from **days to minutes**, improved compliance transparency, and became a **model project for fintech modernization in Serbia**.

---
