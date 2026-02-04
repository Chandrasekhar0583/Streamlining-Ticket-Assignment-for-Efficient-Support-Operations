# Streamlining Ticket Assignment for Efficient Support Operations

## 📌 Overview
This project demonstrates an **automated ticket assignment system** built using **ServiceNow ITSM**.  
Tickets are automatically routed to the correct support groups using **custom tables, ACLs, roles, groups, and Flow Designer workflows**.

---

## 🎯 Objectives
- Automate incident assignment
- Reduce manual effort
- Improve response time
- Enforce role-based security
- Optimize support team workload

---

## 🛠️ Technologies Used
- ServiceNow ITSM
- Flow Designer
- Business Rules
- Assignment Rules
- Access Control Lists (ACLs)
- Custom Tables
- Users, Groups & Roles

---

## 👤 Users
- Created users and configured access
- Assigned roles and groups

📸 Screenshots:
- `screenshots/1.png` – Users list  
- `screenshots/2.png` – User details  

---

## 👥 Groups
- Created support groups
- Assigned managers and members

📸 Screenshots:
- `screenshots/3.png` – Groups list  
- `screenshots/4.png` – Group details  

---

## 🔐 Roles
- Created custom roles
- Assigned roles via groups

📸 Screenshots:
- `screenshots/5.png` – Roles list  

---

## 🗂️ Custom Table
- Created custom table **Operations Related**
- Stored issue and ticket data

📸 Screenshots:
- `screenshots/6.png` – Custom table  

---

## 🛡️ Access Controls (ACLs)
- Implemented Read, Write, Create, Delete ACLs
- Enforced field-level security

📸 Screenshots:
- `screenshots/7.png` – ACL list  
- `screenshots/8.png` – ACL rules  

---

## 🔄 Workflow Automation (Flow Designer)

### Certificate Issues Flow
- Triggered for certificate-related issues
- Automatically assigns to **Certificates** group

📸 Screenshot:
- `screenshots/9.png`

---

### Platform Issues Flow
- Triggered for login and platform-related issues
- Automatically assigns to **Platform** group

📸 Screenshot:
- `screenshots/10.png`

---

## ⚙️ Ticket Routing Logic
| Issue Type | Assigned Group |
|----------|---------------|
| Certificate issues | Certificates |
| Platform / Login issues | Platform |

---

## 🚀 Key Outcomes
- Automated ticket routing
- Reduced response time
- Improved accuracy
- Secure access using ACLs

---

## 🔮 Future Enhancements
- SLA-based routing
- AI-powered categorization
- Reporting dashboards
- Email & notification integrations

---

## 👨‍💻 Author
**Chandra Sekhar Majji**  
ServiceNow Developer | CSA | CAD  
