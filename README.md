# osTicket: Helpdesk Ticketing System (Lifecycle Demo)

**Role:** IT Helpdesk Technician (Simulation)  
**Goal:** Demonstrate full helpdesk ticket workflow — from installation to resolving a real ticket.

---

## 🔧 Project Overview
This project simulates a small company's IT Helpdesk environment using **osTicket**, a web-based open-source support ticket system.

I installed, configured, and demonstrated a full **ticket lifecycle** — showing how IT technicians handle and resolve user issues through proper documentation.

---

## 🧰 Tools & Technologies
- Windows 10 / Server (VM)
- osTicket
- IIS (Internet Information Services)
- MySQL / PHP
- Remote Desktop
- Active Directory (optional integration)

---

## 🧩 Step-by-Step Process

### 1. Installation & Setup
- Installed osTicket on a Windows 10 VM using IIS, PHP, and MySQL.
- Configured email piping and SMTP for ticket notifications.
- Created help topics and SLA plans.

### 2. Ticket Creation
- A simulated user submits a ticket (e.g., *“Cannot connect to VPN”*).
- The ticket appears in the helpdesk dashboard under “New Tickets.”

### 3. Ticket Assignment & Response
- I assigned the ticket to the correct department and priority.
- Responded with troubleshooting questions and updates in osTicket.

### 4. Resolution & Closure
- Verified VPN connection issue.
- Documented root cause and solution.
- Closed the ticket with a resolution summary.

### 5. Reporting
- Checked ticket stats (response time, SLA adherence).

---

## 📸 Screenshots
| Step | Description | Screenshot |
|------|--------------|-------------|
| 1 | Ticket Creation | ![screenshot1](screenshots/create_ticket.png) |
| 2 | Agent View | ![screenshot2](screenshots/agent_view.png) |
| 3 | Ticket Closed | ![screenshot3](screenshots/ticket_closed.png) |

---

## 📹 Demo Video
[![Watch the Demo](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://youtu.be/VIDEO_ID)

---

## 🧠 Lessons Learned
- How to configure a working helpdesk system from scratch.
- Importance of documentation and SLA tracking.
- How to communicate clearly in technical support tickets.

---

## 🚀 Next Steps
- Integrate with Azure AD for SSO.
- Automate ticket categorization using scripts.
