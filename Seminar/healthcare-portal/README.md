Healthcare Portal — Prototype

Overview
- Simple frontend-only prototype demonstrating the requested modules: Patient Management, Appointments & Scheduling, Staff & HR, Pharmacy & Inventory, Billing & Insurance.

How to run
- Open `index.html` in a browser (no server required).

What it does
- Stores data in `localStorage` to demo CRUD flows for each module.
- Includes frontend role-based access control so modules are visible and editable only for permitted staff roles.

Next steps (suggested)
- Replace localStorage with a backend API (Node/Express + SQLite/Postgres).
- Add authentication and proper RBAC.
- Integrate real SMS/email reminders for appointments.

Files
- index.html — main single-page UI
- assets/css/style.css — minimal styles
- assets/js/app.js — simple data handling + sample data
