# SAAS Admin Dashboard 🚀

![Project Status](https://img.shields.io/badge/Status-In_Development-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

> **A high-performance, modular SaaS Admin Dashboard built with an emphasis on atomic component architecture and strict granular validation.**

---

## 📖 Project Overview

**SAAS Admin** is a modern e-commerce management interface designed to handle inventory, data visualization, and user settings. 

Unlike typical dashboard templates, this project was built to demonstrate **scalable frontend architecture**. Every UI element—from buttons to complex forms—is constructed from **atomic, reusable "tiny components"** that stack together. This approach ensures consistency, maintainability, and pixel-perfect design across the application.

### 🌟 Why This Project?
* **Atomic Design:** No hard-coded HTML blobs. Forms are built by stacking reusable `InputGroup`, `ValidationLabel`, and `ActionBlock` components.
* **Granular Validation:** Custom-built validation logic that creates a "live" feedback loop for users (e.g., auto-capitalization, dynamic tooltips).
* **Performance Focused:** Minimal re-renders and optimized state management for data visualization.

---

## 🛠️ Tech Stack

**Core:**
* ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) **React.js** (Component Architecture)
* ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white) **Vite** (Build Tool)
* ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white) **Tailwind CSS** (Utility-First Styling)

**Data & State:**
* **Recharts** (Data Visualization)
* **Context API / Custom Hooks** (State Management)
* **Regex** (Advanced Validation Patterns)

---

## ⚡ Key Features (MVP Scope)

### 🔐 1. Secure Access Gateway (Authentication)
* Custom **Sign-In** and **Sign-Up** modules.
* **Atomic Logic:** Inputs auto-capitalize first letters; Passwords have "live" strength requirements checking.
* *Status: In Progress*

### 📊 2. Executive Command Center (Dashboard)
* Real-time data visualization using responsive line and donut charts.
* Key Metric Cards (Revenue, Churn, Active Users) built as stateless presentation components.
* *Status: Planned*

### 📦 3. Inventory Grid System
* Rich data tables with **Sort**, **Filter**, and **Pagination** functionalities.
* Dynamic status badges (e.g., "Low Stock" warning indicators).
* *Status: Planned*

### ✏️ 4. Product Editor (CRUD)
* A complex "Mega Form" for adding/editing products.
* Features atomic drag-and-drop image zones and currency-formatted inputs.
* *Status: Planned*

### ⚙️ 5. User Preferences Hub
* Global state management examples (Theme Toggling: Dark/Light Mode).
* Profile management with immediate optimistic UI updates.
* *Status: Planned*

---

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites
* Node.js (v20+)
* npm

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/riteshkrdev/saas-admin-dashboard.git](https://github.com/riteshkrdev/saas-admin-dashboard.git)
    ```

2.  **Navigate to project directory**
    ```bash
    cd saas-admin-dashboard
    ```

3.  **Install dependencies**
    ```bash
    npm install
    ```

4.  **Start the development server**
    ```bash
    npm run dev
    ```

---

<!-- ## 🗺️ Roadmap & Future Improvements

While the current MVP focuses on core frontend administration, future updates will include:
- [ ] **Backend Integration:** Connecting to a Node.js/Express API.
- [ ] **Role-Based Access Control (RBAC):** Admin vs. Editor permissions.
- [ ] **Export Functionality:** CSV/PDF export for Inventory reports.

--- -->

## 📬 Contact & Portfolio

**Ritesh Kumar** *Frontend Engineer* [LinkedIn](https://linkedin.com/in/riteshkrdev) | [Portfolio](https://stilltoupdate.com)

## Direct open Dev Branch: Current Working Branch
[Repo Link](https://github.com/riteshkrdev/saas-admin-dashboard/tree/dev)


# React + Vite Speedy Web Compiler (SWC)