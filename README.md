# 🛒 AMZN Mini E-Commerce Project (Jira + Confluence + GitHub Showcase)

This is a simulated Agile project for an e-commerce platform named **AMZN**, inspired by Amazon. The goal was to build a working MVP (Minimum Viable Product) followed by additional feature expansion. The project was executed using **Scrum methodology** over **2 sprints (2 weeks each)** and tracked using **Jira**, with documentation in **Confluence**.

---

## 📌 Project Overview

- **Project Type:** Agile Mini Project (Scrum)
- **Tools Used:** Jira, Confluence, GitHub
- **Sprints:** 2
- **Versioned Releases:** AMZN V1.1 (MVP), AMZN V1.2 (Feature Expansion)

---

## 🗂️ Epics & User Stories

### 🔹 Epic 1: Website Development (Core)
- ✅ AZ-5: As a user, I want to browse products by categories.
- ✅ AZ-6: As a user, I want to create a cart and add/remove items.
- ✅ AZ-7: As a user, I want to checkout and simulate a dummy payment with confirmation.

### 🔹 Epic 2: Bug Fixes & Performance
- 🐞 AZ-13: AMEX BIN not accepted in payment gateway (fixed in Sprint 2)

### 🔹 Epic 3: Feature Expansion
- ✅ AZ-14: Add AMZN Wallet feature
- ✅ AZ-15: Add Bills & Recharge (electricity, gas, mobile)
- ✅ AZ-16: Add AMZN Gift Vouchers
- ✅ AZ-17: Add Travel Booking (bus, train, flight) in collaboration with a ticketing partner (e.g., MMT)

---

## 📅 Sprint Timeline & Releases

| Sprint    | Duration           | Key Deliverables                          | Release     |
|-----------|--------------------|-------------------------------------------|-------------|
| Sprint 1  | Mar 14 – Mar 28, 2025 | Website MVP (Home, Cart, Checkout, Dummy Payment), Bug reported | AMZN V1.1 |
| Sprint 2  | Mar 29 – Apr 11, 2025 | Bug fix, AMZN Wallet, Recharge, Gift Vouchers, Travel Booking | AMZN V1.2 |

---

## 💳 Dummy Payment Logic

To simulate the checkout process, a **dummy payment gateway** was used. Users can enter any valid-looking card number (e.g., `4111 1111 1111 1111`) and receive an **Order Confirmation** message.

- No real transactions were processed.
- Bug Encountered: AMEX BIN range (`34xxxxxxxxxxxxxx`) was initially blocked.
- Bug was fixed in Sprint 2.

---

## 📘 Confluence Documentation

Project documentation included:
- Sprint Planning
- Product Backlog
- Sprint Review & Retrospective
- Release Notes for AMZN V1.1 and V1.2

📎 [Confluence Link (Sample Placeholder)](https://your-confluence-site.atlassian.net/wiki/spaces/AMZN)

---

## 🧑‍💻 How This Project Helps

This project demonstrates:
- End-to-end project ownership using Agile (Scrum)
- Jira for task tracking, Epics, Sprints, and Versions
- Understanding of user stories, bug fixing, and feature rollout
- Cross-platform feature planning (wallets, vouchers, travel)

---

## ✅ Future Scope (Optional Additions)
- Integration with real payment APIs
- Authentication system
- Review & rating system
- Order tracking dashboard

---

amzn-jira-project/
├── README.md                      # Project overview with Jira details and links
│
├── docs/
│   ├── screenshots/               # Jira screenshots (timeline, bug, etc.)
│   │   ├── jira_timeline.png
│   │   └── jira_bug_amex_bin.png
│   └── jira_exports/
│       └── jira_issues_amzn.csv  # Exported CSV of all Jira issues

