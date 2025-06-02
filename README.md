# Project_Opencart


## Overview

Welcome to the OpenCart project. This document is created and maintained by a senior manual QA tester with 20+ years of experience in eCommerce and software quality assurance.

OpenCart is an open-source, PHP-based online shopping cart system. It offers a robust administrative interface and a flexible user experience.

This README will guide QA team members, business analysts, and other stakeholders through the QA process for this project.

---

## 📌 Project Objectives

- Ensure stability and functionality of the OpenCart platform across modules.
- Validate core eCommerce flows: browsing, searching, checkout, payment, and admin management.
- Identify and report bugs in early development phases.
- Facilitate regression, smoke, UAT, and exploratory testing with structured processes.

---

## 🔧 System Requirements

Ensure the following environments are set up before testing:

### Client Side:
- Browser: Chrome (latest), Firefox, Safari, Edge
- OS: Windows 10/11, macOS, Ubuntu (for cross-platform validation)
- Screen resolutions: 1366x768, 1920x1080 (responsive testing)

### Server Side:
- PHP 7.4+
- MySQL 5.7+
- Apache/Nginx
- OpenCart version: 3.x.x (confirm with Dev)

---

## ✅ Test Types Covered

1. **Smoke Testing** – Verify key functionalities are working after deployment.
2. **Sanity Testing** – Validate that reported issues have been fixed.
3. **Functional Testing** – Deep testing of all features (e.g., product search, cart, checkout).
4. **Regression Testing** – Ensure that new changes do not break existing features.
5. **Exploratory Testing** – Simulate real user behavior to uncover hidden bugs.
6. **UI/UX Validation** – Confirm layout, alignment, colors, and responsiveness.
7. **Cross-browser Testing** – Validate consistent behavior across browsers.
8. **Negative Testing** – Enter invalid input to test system error handling.

---

## 🧪 Modules to Test

| Module             | Key Areas to Validate                        |
|--------------------|----------------------------------------------|
| **Home Page**      | Banners, navigation, responsiveness          |
| **Product Pages**  | Images, descriptions, price, stock           |
| **Cart**           | Add/remove items, quantity updates           |
| **Checkout**       | Guest & Registered user checkout, coupons    |
| **Payment**        | PayPal, Stripe, COD – based on config        |
| **User Account**   | Login, registration, password recovery       |
| **Admin Panel**    | Product/category creation, order tracking    |
| **Reports**        | Sales, customers, inventory reports          |

---

## 🛠️ Test Data

Prepare and use consistent test data for predictability:

- Test Products: 10 dummy SKUs (varying price/stock)
- Users: 
  - Registered: `qauser@example.com / Test@123`
  - Guest checkout details
- Payment: Use sandbox/test API keys only

---

## 🔄 Test Cycle & Process

1. **Receive Build Notification** (from dev or CI/CD)
2. **Test Execution** (refer Test Scenarios & Checklists)
3. **Log Bugs in Tracker** (JIRA, TestRail, or Excel)
4. **Retest on Fixes**
5. **Daily/Weekly Status Reports** (email or dashboard)
6. **Final Sign-off after Regression**

---

## 🐞 Bug Reporting Best Practices

- Use clear and concise titles
- Include steps to reproduce
- Attach screenshots/videos where needed
- Provide browser/OS info
- Assign appropriate severity & priority

---

## 📋 Sample Test Checklist (Functional)

- [x] User can register with valid email
- [x] Invalid email shows appropriate error
- [x] Product added to cart reflects correct total
- [x] Discount coupons apply correctly
- [x] Admin can delete a product
- [x] Out-of-stock product disables "Add to Cart" button

---


