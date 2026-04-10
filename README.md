# Unified Employee Attendance & Productivity System

## Overview
This is a comprehensive full-stack solution designed to manage employee attendance, leave tracking, productivity monitoring, and access control. It features a modern, responsive UI, a robust backend API, and a .NET microservice for advanced analytics and rule evaluation.

## Features
- **Authentication**: Secure user registration and login using JWT. Role-based access control (Admin, HR, Employee).
- **Admin Panel**: Dedicated admin interface with system actions and monitoring.
- **Dashboard**: Interactive dashboard with quick stats, charts, and navigation.
- **Attendance**:
  - "Punch In" and "Punch Out" functionality.
  - View personal attendance history.
  - Automatic work hour calculation.
  - Task hours tracking per attendance record.
- **Leave Management**:
  - Apply for different types of leaves (Sick, Casual, Earned).
  - View leave history and status (Pending, Approved, Rejected).
  - Admin/HR interface to approve/reject leaves.
- **Productivity (Task Management)**:
  - Admin can assign tasks to employees with project names.
  - Employees can view assigned tasks and update status (Pending, In Progress, Completed).
  - Timer functionality to log work hours per task.
  - Productivity score calculation.
  - Visual indicators for task status.
- **Rules Engine** (.NET Service):
  - Define custom access control rules.
  - Automated rule evaluation.
  - Alert generation for rule violations.
- **System Actions** (Admin Only):
  - Run reconciliation (detect attendance/leave conflicts).
  - Calculate productivity scores.
  - Evaluate access control rules.
  - View system alerts.

## Tech Stack
- **Frontend**: React (Vite), CSS (Modern/Glassmorphism)
- **Backend**: Node.js, Express.js
- **Microservice**: .NET Core (ASP.NET Core)
- **Database**: MongoDB (Mongoose)
- **Authentication**: JSON Web Tokens (JWT), bcryptjs

## License

MIT License

Copyright (c) 2026 GURKEERAT KAUR

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---
