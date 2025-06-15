# 🛠️ Project Charter: Reward based E-Commerce Portal for Students

---

## 🧾 Executive Summary
RewardCoin is a coin-based e-commerce reward portal designed for school environments. Students can complete assigned tasks to earn coins and redeem them for listed products, similar to Amazon or Flipkart — but with coins instead of cash. It features role-based dashboards for Admin, Teachers, and Parents/Students, aiming to gamify motivation and streamline academic recognition.

---

## 🎯 Project Goal (SMART)

**Specific**: Create a school-specific coin-based reward platform  
**Measurable**: Enable at least 10 tasks, 20 student profiles, and 10 product redemptions within 45 days  
**Achievable**: Using current web stack and available time over 5–6 weeks  
**Relevant**: Aligns with educational motivation and reward systems  
**Time-bound**: MVP ready and functional by August 31, 2024

---

## 📦 Deliverables

- Admin Dashboard with:
  - Product management (CRUD)
          CRUD = Create: Add new products (name, image, price in coins, description); Read: View product list, search, filter;
          Update: Edit product details (price, stock, images); Delete: Remove a product
  - Task and reward configuration
  - Inventory/order tracking
- Teacher Dashboard with:
  - Student list by class/section
  - Task assignment and reward approval
- Parent/User Dashboard:
  - Register and manage children
  - View coin balance, redeem rewards
- Reward Store Interface
- Basic SMS notification on activation
- GitHub Repo with full documentation

---

## 💼 Business Case / Background

Many schools offer tangible rewards for academic or behavioral achievements, but these systems are manual, inconsistent, and often untracked. RewardCoin digitizes this process, enabling transparency, accountability, and motivation through a gamified portal that integrates reward tasks with a point-based e-commerce system.

---

## 💰 Benefits, Costs, and Budget

### 🎁 Benefits:
- Boosts student engagement and discipline
- Enables teachers to reward specific behaviors or milestones
- Reduces admin overhead in tracking reward inventory
- Transparent and centralized system

### 💸 Costs:
- Development time (~100–150 hours)
- Hosting (~₹500–1000/month for MVP)
- Optional SMS API (~₹250 for 1000 messages)

### 📊 Budget (Estimated for MVP): (Minimum Viable Product)
| Item               | Cost Estimate   |
|--------------------|-----------------|
| Web hosting        | ₹800            |
| SMS Gateway        | ₹250            |
| Dev Time (if paid) | ₹20,000+        |
| GitHub & Tools     | Free            |
| **Total**          | **₹1,000 – ₹20,000** (depending on in-house effort)

---

## 🧾 Scope & Exclusions

### ✅ In Scope (MVP):
- Role-based login (Admin, Teacher, Parent/Student)
- Task-based coin rewards
- Product catalog with coin pricing
- SMS-based activation workflow
- Coin ledger and redemption flow

### ❌ Exclusions:
- Real-money payment gateway
- Full delivery logistics
- Auto-grading or AI task evaluation
- Advanced analytics/reporting

---

## 👥 Project Team

| Role              | Person             |
|-------------------|--------------------|
| Project Sponsor    | School Leadership  |
| Project Manager    | Dr. Sudheer Kumar  |
| Developer(s)       | In-house / GitHub contributors |
| QA/Testing         | TBD (manual for now) |
| Stakeholders       | Students, Teachers, Admin, Parents |

---

## 🧮 Measuring Success

| Metric                              | Target                |
|-------------------------------------|------------------------|
| Student task completion rate        | ≥ 70% within 30 days   |
| Active user registrations           | ≥ 25 parents/students  |
| Product redemptions (via coins)     | ≥ 10 successful orders |
| Admin and Teacher engagement        | Daily logins by 3+ users|
| Functional dashboards               | All 3 roles tested     |
| Deployment                          | Live MVP by August 31, 2024 |

---
