![image](https://github.com/user-attachments/assets/9ab7b517-43ce-48cf-966f-39339af203ae)
# Building a Comprehensive Ticketing System with osTicket: Step-by-Step Projects

## Configuring Roles, Teams, and SLA Settings in osTicket

This project demonstrates the configuration of roles, teams, and Service Level Agreements (SLAs) within the osTicket platform. Below are the step-by-step configurations undertaken to ensure a robust and efficient ticketing system.

---
### Environments and Technologies Used
- Localhost Server
- osTicket Platform
- Web Browser (Chrome/Edge)

### Operating Systems Used
- Windows 10 (21H2)

### List of Prerequisites
1. Install and configure a local server (e.g., XAMPP or WAMP).
2. Install osTicket on the localhost.
3. Access the Admin Panel and Agent Panel of osTicket.
4. Create and configure Roles, Departments, and Teams within osTicket.
5. Enable/disable ticket creation settings for users.

---

### Admin and User Access URLs
- **Admin/Analyst Login Page**: [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
- **End Users osTicket URL**: [http://localhost/osTicket](http://localhost/osTicket)

---

### Configuration Overview

#### 1. **Acknowledge Agent Panel vs Admin Panel**
Understanding the separation of roles between Agents (responders) and Admins (managers).

#### 2. **Configure Roles**
- Navigate to **Admin Panel → Agents → Roles**
- Created the role:
  - **Supreme Admin**
    ![image](https://github.com/user-attachments/assets/befcd1eb-1e43-4e3b-a129-58ce84d5fb28)


#### 3. **Configure Departments**
- Navigate to **Admin Panel → Agents → Departments**
- Added departments for ticket visibility:
  - **SysAdmins**
    ![image](https://github.com/user-attachments/assets/20d9c903-2253-4dcf-8e2a-3361cc162018)


#### 4. **Configure Teams**
- Navigate to **Admin Panel → Agents → Teams**
- Teams are configured to pull agents from different departments:
  - **Online Banking**
    ![image](https://github.com/user-attachments/assets/255dc3e7-6f8c-48f3-a4b4-4bfa7541b7ec)


#### 5. **Allow Anyone to Create Tickets**
- Navigate to **Admin Panel → Settings → User Settings**
- Disabled open registration:
  - **Registration Required**: Require login for ticket creation.
    ![image](https://github.com/user-attachments/assets/bea9fab1-8f87-463f-b1eb-5f9fd7a3235b)


#### 6. **Configure Agents**
- Navigate to **Admin Panel → Agents → Add New**
- Added agents:
  - **Jane** (Dept: SysAdmins)
  - **John** (Dept: Support)
    ![image](https://github.com/user-attachments/assets/39e03d6f-d87a-4ab7-b38a-d20f1b760b07)


#### 7. **Configure Users**
- Navigate to **Agent Panel → Users → Add New**
- Added end users:
  - **Karen**
  - **Ken**
    ![image](https://github.com/user-attachments/assets/9e9c42df-dacf-46fe-98c6-a8d086e9fa70)


#### 8. **Configure SLA**
- Navigate to **Admin Panel → Manage → SLA**
- SLA Policies configured:
  - **Sev-A**: 1 hour grace period, 24/7 schedule.
  - **Sev-B**: 4 hour grace period, 24/7 schedule.
  - **Sev-C**: 8 hour grace period, business hours schedule.
    ![image](https://github.com/user-attachments/assets/f4539c5a-6517-4588-9ecb-39beb880f69b)


#### 9. **Configure Help Topics**
- Navigate to **Admin Panel → Manage → Help Topics**
- Added help topics for ticket creation:
  - **Business Critical Outage**
  - **Personal Computer Issues**
  - **Equipment Request**
  - **Password Reset**
  - **Other**
    ![image](https://github.com/user-attachments/assets/ae67bbf2-f0aa-473f-822e-85684d070883)


---

### Key Learnings and Skills Gained
- **Administrative Configuration**: Learned how to assign and manage roles, teams, and departments.
- **Service Level Agreements**: Gained insights into defining and applying SLA policies to tickets.
- **System Accessibility**: Configured user registration and access settings to control ticket submission.

---

This project showcases the administrative and analytical aspects of configuring an efficient ticketing system with osTicket. It highlights the practical experience gained in user management and SLA application.
