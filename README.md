# Leave Management System

> A comprehensive digital leave management solution for organizations, replacing paper-based processes with automated workflows and real-time tracking.

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Live Demo:** [senf.af/leave](https://senf.af/leave) (Login required)

---

## 🎯 Overview

Built for **Lapis Group** to digitize their leave management process, this system serves **60+ employees** across multiple departments with role-based dashboards, automated approval workflows, and real-time balance tracking.

### Key Features

✅ **Employee Self-Service**
- Submit leave requests with half-day support
- Real-time balance tracking across 7 leave types
- View request status and history
- Automatic email notifications

✅ **Manager Dashboard**
- Approve/reject team leave requests
- Team analytics and stats cards
- Team leave balance tracker
- Searchable employee records

✅ **HR Dashboard**
- Organization-wide leave visibility
- Complete employee leave tracker
- Export-ready reporting
- User management

✅ **Smart Workflows**
- Sick leave > 1 day requires HR approval
- Automatic balance deduction on approval
- Email notifications at each step
- Color-coded status indicators

---

## 🏗️ Architecture

### Frontend
- **HTML5/CSS3** — Responsive design with custom CSS variables
- **Vanilla JavaScript** — Real-time calculations, form validation
- **Google Fonts** — Playfair Display + DM Sans

### Backend
- **PHP** — Server-side logic and workflows
- **MySQL** — Relational database with proper indexing
- **PDO** — Prepared statements for security

### Features
- Role-based access control (Employee, Manager, HR, Admin)
- Session-based authentication
- Email notifications via PHP mail()
- Mobile-responsive tables with horizontal scroll
- Half-day leave calculations (0.5 days)

---

## 📊 Leave Types Supported

| Leave Type | Default Entitlement |
|------------|---------------------|
| Annual Leave | 20 days |
| Sick Leave | 21 days |
| Casual Leave | 10 days |
| Hajj Leave | 15 days |
| Maternity Leave | 90 days |
| Marriage Leave | 3 days |
| Urgent Leave | 5 days |
| Educational Leave | 30 days |

All entitlements are configurable per employee via database.

---

## 🔐 Security Features

- Password hashing with bcrypt
- Prepared SQL statements (PDO)
- Session-based authentication
- Role-based authorization
- CSRF protection on forms
- Input validation and sanitization

---

## 📸 Screenshots

### Employee Dashboard
![Employee View](screenshots/employee-dashboard.png)
*Employee can view balances and submit requests*

### Manager Dashboard
![Manager View](screenshots/manager-dashboard.png)
*Manager approves requests with team analytics*

### HR Leave Tracker
![HR Tracker](screenshots/hr-tracker.png)
*Complete organizational leave overview*

---

## 🚀 Deployment

**Production Environment:**
- **Platform:** Hostinger Shared Hosting
- **PHP Version:** 8.1+
- **Database:** MySQL 5.7+
- **Domain:** senf.af/leave

**Server Requirements:**
- PHP 8.0 or higher
- MySQL/MariaDB
- PDO extension enabled
- Mail function configured

---

## 💡 Use Cases

Perfect for:
- Small to medium organizations (50-200 employees)
- Companies moving from paper-based systems
- Teams needing approval workflows
- HR departments requiring centralized tracking
- Organizations with multiple leave policies

---

## 🛠️ Technical Highlights

- **Zero external dependencies** — Pure PHP/MySQL stack
- **Mobile-first design** — Responsive on all devices
- **Fast performance** — Optimized queries with indexing
- **Easy maintenance** — Clean, documented codebase
- **Scalable architecture** — Designed for growth

---

## 📝 Project Timeline

- **Development:** February 2026
- **Deployment:** March 2026
- **Status:** Production (Active)
- **Users:** 60+ employees

---

## 👨‍💻 Developer

**Shams Haqyar**  
Team Lead — Technology, Lapis Group

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shams-haqyar-373020136/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/shamsulhaqHaqyar)

---

## 📄 License

**Note:** This is a showcase repository. The actual source code is proprietary and maintained in a private repository.

For inquiries about custom implementations or consultations, please contact via LinkedIn.

---

<p align="center">
  <i>Transforming HR workflows through practical technology solutions.</i>
</p>
```

---

## **📁 What to Include in Public Repo:**
```
lapis-leave-system/
├── README.md (above)
├── screenshots/
│   ├── employee-dashboard.png
│   ├── manager-dashboard.png
│   ├── hr-tracker.png
│   └── mobile-view.png
└── LICENSE (optional)
