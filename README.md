# Employee-Management-System
Build &amp; Deploy Full Stack Employee Management System in React js | MERN Stack Project

<img width="1917" height="870" alt="image" src="https://github.com/user-attachments/assets/1ab151dd-0e0c-414b-8783-5a192f868230" />

## **Introduction**
**EMS-Pro** is a comprehensive, modern workforce management solution designed to streamline HR operations and empower employees through a centralized digital portal. Built using the **MERN stack**, the application provides a secure, role-based environment where administrators can oversee organizational health while employees manage their professional data. From real-time attendance tracking to automated payslip generation, the platform transforms manual HR tasks into a seamless digital experience.

## **Problem Statement**
Many growing organizations struggle with fragmented employee data, relying on outdated spreadsheets or paper-based systems for attendance and leave tracking. These manual processes are prone to human error, lack transparency for employees regarding their payroll/leave balances, and often fail to provide secure, role-based access to sensitive personnel information.

## **Proposed Solution**
The Employee Management System offers an integrated full-stack solution that digitizes the entire employee lifecycle. By utilizing **Role-Based Access Control (RBAC)**, the system provides two distinct interfaces: an **Admin Portal** for high-level oversight and an **Employee Portal** for self-service. The integration of **Inngest** for background jobs and **AI-powered reviews** ensures the system is not only functional but follows modern, scalable engineering standards.

## **Objectives**
* **Role-Based Authentication:** Secure login for Admins and Employees with distinct permissions and dashboard views.
* **Attendance Tracking:** A digital system for employees to log presence and for admins to monitor workforce availability.
* **Leave Management:** A streamlined workflow for leave requests, approvals, and balance tracking.
* **Automated Payroll:** Generate and manage digital payslips, reducing administrative overhead.
* **Scalable Architecture:** Develop a robust REST API and a clean MongoDB schema capable of handling growing organizational data.

## **Project Scope**
* **Admin Portal:** Manage employee records (CRUD), approve/reject leave requests, monitor attendance trends, and generate payroll.
* **Employee Portal:** View personal profile, check-in/out for attendance, apply for leave, and download monthly payslips.
* **Backend API:** A secure Node.js/Express server handling authentication, business logic, and database communication.
* **AI Integration:** Utilizing CodeRabbit for AI-powered code reviews to maintain high-quality, production-ready code.

## **Technology Stack**

| Category | Technology |
| :--- | :--- |
| **Frontend** | React JS, Tailwind CSS, Vite |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (Mongoose ODM) |
| **Authentication** | JSON Web Tokens (JWT) & Bcrypt.js |
| **Background Jobs** | Inngest (Scheduling & Workflows) |
| **Code Quality** | CodeRabbit (AI-Powered Reviews) |

## **Project Management & Workflow**
* **Version Control:** Git & GitHub for collaborative development and version history.
* **API Testing:** Postman for testing and documenting RESTful endpoints.
* **Deployment:** Vercel (Frontend) and Render/Railway (Backend).
* **Automation:** Inngest for handling background tasks like automated status updates or notification triggers.

## **Security & Reliability Plan**
* **Password Hashing:** Utilizing **Bcrypt.js** to ensure sensitive user credentials are never stored in plain text.
* **Protected Routes:** JWT implementation to prevent unauthorized access to Admin-only or Employee-specific data.
* **Data Integrity:** Mongoose schemas ensure that all employee and financial records follow strict validation rules.
* **CORS & Environment Protection:** Secure API configuration to prevent unauthorized cross-origin requests and protection of API keys via `.env` management.

---

### **Key Learning Outcomes**
* Mastering the **MERN** (MongoDB, Express, React, Node) architecture.
* Implementing complex **Role-Based Access Control (RBAC)**.
* Managing asynchronous background tasks with **Inngest**.
* Designing professional UIs that balance aesthetics with functional utility.


