# project-docs-project-charter.md
# 🛠️ Project Charter: RewardCoin – E-Commerce Portal for Schools

## 📌 Project Title
**RewardCoin** – A Coin-Based Educational E-Commerce Portal

---

## 🎯 Project Purpose
To build a role-based reward system integrated with an e-commerce portal, where students can earn reward coins by completing tasks assigned by teachers and redeem those coins for products listed by the admin. This promotes student motivation and streamlines school-based reward systems using technology.

---

## 🥅 Project Objectives

- Enable Admins to manage products, inventory, and user accounts
- Provide Teachers with the ability to assign tasks and reward coins
- Allow Parents to register accounts and manage child profiles
- Offer Students a gamified dashboard to view tasks and redeem coins
- Simulate an e-commerce environment using coins instead of currency

---

## 📦 Scope

### ✅ In Scope (Phase 1)
- Admin dashboard with:
  - Product management (CRUD)
  - Inventory & order tracking
  - Task creation and coin assignment
  - User account approval workflows
- Parent login and child registration (with admin verification)
- Teacher dashboard for:
  - Class/student view
  - Task assignment
  - Task review & coin deposit
- Student dashboard with:
  - Earned coins view
  - Reward store access (purchase via coins)
  - Task list display
- SMS notification system for account activation
- Coin ledger system for reward tracking

### ❌ Out of Scope (for MVP)
- Real payment gateway integration
- Physical delivery logistics or courier APIs
- AI-based task evaluation
- Multilingual support

---

## 👥 Stakeholders

| Role              | Name / Description                        |
|-------------------|--------------------------------------------|
| Project Manager   | Dr. Sudheer Kumar                          |
| Product Owner     | School Leadership                          |
| Developer Team    | Internal / GitHub Contributors             |
| Users             | Admin, Teachers, Parents, Students         |

---

## 🗓️ Timeline

| Phase                   | Duration  | Deliverables                          |
|------------------------|-----------|----------------------------------------|
| 🟩 Planning             | 1 Week    | Charter, Backlog, Initial Wireframes   |
| 🟦 Sprint 1             | 2 Weeks   | Admin Module, User Login, Product UI   |
| 🟨 Sprint 2             | 2 Weeks   | Task Modules, Dashboards, Coin Logic   |
| 🟪 Testing & Deployment | 1 Week    | QA, Bug Fixes, Final Deployment        |

---

## 🧮 Success Criteria

- Admin, Teacher, and User dashboards fully operational
- Coin-based e-commerce functionality (view → add to cart → purchase)
- Task-to-coin logic integrated across all roles
- At least 3 child accounts, 10 products, and 5 tasks successfully demonstrated
- Functional SMS-based user activation flow
- Public GitHub repository with full documentation and issue tracking

---

## ⚠️ Risks & Mitigation

| Risk                                  | Mitigation Strategy                        |
|---------------------------------------|---------------------------------------------|
| Delay in SMS gateway or API integration | Use simulated SMS logs or local messages   |
| Complex child-parent-user logic        | Build user model modularly, test thoroughly|
| Coin logic mismatch across roles       | Centralize coin logic and maintain a ledger|

---

## 🔄 Change Control

All significant changes to project scope, user flow, or technical architecture must be approved by the project owner and logged via GitHub Issues or Pull Requests.
