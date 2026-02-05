# entra-id-iam-project
🔐 Identity & Access Management using Microsoft Entra ID
📌 Project Overview

This project demonstrates a real-world implementation of Identity and Access Management (IAM) using Microsoft Entra ID. The objective is to manage users, groups, roles, and secure access using MFA, Conditional Access, and Privileged Identity Management (PIM).

🎯 Objectives

Create and manage users and groups

Assign roles using RBAC

Enforce Multi-Factor Authentication (MFA)

Implement Conditional Access policies

Secure admin access using PIM

Monitor activities using Sign-in and Audit logs

🏗️ Architecture
Users → Groups → Roles  
       ↓  
Conditional Access → MFA  
       ↓  
PIM → Admin Roles  
       ↓  
Monitoring → Logs

🛠️ Technologies Used

Microsoft Entra ID

Azure Portal / Entra Admin Center

Microsoft Authenticator

RBAC

Conditional Access

Privileged Identity Management

📂 Project Structure
/entra-id-iam-project
│
├── README.md
├── docs/
│   ├── users-groups.md
│   ├── roles.md
│   ├── mfa.md
│   ├── conditional-access.md
│   ├── pim.md
│   └── logs.md
│
└── screenshots/
    ├── create-users.png
    ├── ca-policy.png
    └── pim-activation.png

🚀 Implementation Steps
1. User & Group Management

Created users: user1, user2, admin1

Created groups: HR-Team, IT-Admins

Assigned users to appropriate groups

2. Role Assignment

Assigned User Administrator to admin1

Assigned Global Reader to user2

3. Multi-Factor Authentication

Enabled Microsoft Authenticator and SMS

Tested MFA during user login

4. Conditional Access

Policy: Require MFA for HR-Team

Applied to all cloud apps

5. Privileged Identity Management

Made admin1 eligible for Global Administrator

Configured MFA and approval for role activation

6. Monitoring & Logs

Verified sign-in logs for MFA success

Checked audit logs for role changes

🔍 Use Case Scenarios
Scenario	Solution
Employee login	MFA enforced
HR accessing apps	CA policy applied
Admin performing tasks	PIM activation required
Security review	Logs monitored
📊 Key Learnings

Understood Zero Trust implementation

Gained hands-on experience with RBAC

Learned how to protect privileged accounts

Learned how to troubleshoot sign-in issues

📈 Future Enhancements

Implement Access Reviews

Integrate SaaS apps (Salesforce, ServiceNow)

Configure Passwordless authentication

Setup Identity Protection policies

🧠 Skills Demonstrated

Microsoft Entra ID, IAM, MFA, Conditional Access, PIM, RBAC, Zero Trust, Cloud Security

📝 Author

Naveen Gajja
Aspiring IAM / Cloud Security Engineer
