# Manual Testing Project — nopCommerce E-Commerce Application

![Testing](https://img.shields.io/badge/Type-Manual%20Testing-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Tool](https://img.shields.io/badge/Tool-Excel%20%7C%20JIRA-orange)
![Test Cases](https://img.shields.io/badge/Test%20Cases-105%2B-purple)
![Bugs](https://img.shields.io/badge/Bugs%20Reported-10-red)

---

## Project Overview

This project demonstrates end-to-end manual testing of the **nopCommerce**
open-source e-commerce web application. It covers 60 test scenarios,
105+ detailed test cases, and 10 documented bug reports across all
major functional modules of the application.

> **Application Under Test:** [demo.nopcommerce.com](https://demo.nopcommerce.com)
> **Testing Type:** Functional Manual Testing
> **Environment:** Windows 11 | Chrome | Firefox

---

## Objective

- Validate core functionality of the nopCommerce e-commerce application
- Identify, document, and report defects with clear reproduction steps
- Ensure the application meets expected functional requirements
- Demonstrate real-world QA skills: test design, execution, and bug reporting

---

## Scope — Modules Tested

| Module | Description |
|---|---|
| User Registration | Sign-up with valid/invalid/duplicate inputs |
| Login / Logout | Authentication, session management, Remember Me |
| Password Reset | Forgot password and change password flows |
| Home Page | Navigation, featured products, footer links |
| Product Search | Keyword, filter, partial match, edge cases |
| Product Catalogue | Listing, sorting, filtering, pagination, view toggle |
| Product Details | Images, stock status, SKU, reviews, related products |
| Shopping Cart | Add, update, remove, quantity limits, total calculation |
| Wishlist | Add, remove, move to cart |
| Compare Products | Add to compare, comparison table |
| Checkout | Guest checkout and registered user end-to-end flow |
| Payment | Credit card, cheque/money order |
| Discount & Coupons | Valid, invalid, expired coupon codes |
| Gift Cards | Apply and partial payment with gift card |
| Reward Points | Earn after purchase, redeem at checkout |
| Order Management | Confirmation email, order history, re-order |
| My Account | Profile update, address management |
| Newsletter | Subscribe and unsubscribe |
| Product Reviews | Submit review, approval flow |
| Contact Us | Form submission and field validation |

---

## Test Artifacts

| Artifact | Sheet | Description |
|---|---|---|
| Test Scenarios | Sheet 1 | 60 high-level test scenarios mapped to modules |
| Test Cases | Sheet 2 | 105+ detailed test cases with preconditions, steps, expected & actual results |
| Bug Report | Sheet 3 | 10 documented bugs with severity, priority, and reproduction steps |

**File:** `nopCommerce_Testing.xlsx`

---

## Bug Summary

| Bug ID | Module | Summary | Severity |
|---|---|---|---|
| BUG_001 | Password | Forgot password shows success for unregistered email | Medium |
| BUG_002 | Shopping Cart | Add to Cart enabled for out-of-stock products | High |
| BUG_003 | Product Reviews | Review visible immediately without admin approval | Medium |
| BUG_004 | Shopping Cart | Mini-cart total not updated after coupon applied | Low |
| BUG_005 | Product Search | Case-sensitive search returns inconsistent results | Medium |
| BUG_006 | Product Catalogue | Price: Low to High sort not working correctly | High |
| BUG_007 | Home Page | Social media links open in same tab instead of new tab | Low |
| BUG_008 | Order Management | Estimated delivery date missing from order detail page | Low |
| BUG_009 | Shopping Cart | Same product added twice creates duplicate line items | Medium |
| BUG_010 | Product Catalogue | Breadcrumb not updated when coming from search results | Low |

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Writing and tracking test scenarios, test cases, bug reports |
| JIRA | Bug tracking and defect lifecycle management |
| nopCommerce Demo | Application under test |
| Chrome / Firefox | Test execution browsers |

---

## How to Use

1. Clone or download this repository
2. Open `nopCommerce_Testing.xlsx` in Microsoft Excel or Google Sheets
3. Navigate between sheets:
   - **Sheet 1 – Test Scenarios:** High-level coverage overview
   - **Sheet 2 – Test Cases:** Step-by-step cases with pass/fail status
   - **Sheet 3 – Bug Report:** Defects with steps to reproduce
4. To execute tests yourself, visit the live demo:
   👉 https://demo.nopcommerce.com

---

## Project Structure

```
Manual-Testing-nopCommerce/
│
├── nopCommerce_Testing.xlsx   ← Main test artefact (3 sheets)
└── README.md                  ← Project documentation
```

---

## Author

**Sanskruti Parab**
QA Tester | Manual Testing Enthusiast

- GitHub: [@SanskrutiParab](https://github.com/SanskrutiParab)
- LinkedIn: www.linkedin.com/in/sanskruti-parab-431582364

---

*Feel free to fork this repository or use it as a reference for your own QA portfolio.*
