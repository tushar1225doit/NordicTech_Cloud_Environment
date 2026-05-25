# NordicTech Solutions

## Overview

NordicTech Solutions is a fictional small technology company used to simulate a real-world cloud administration and IT support environment using Azure and Microsoft 365.

The company contains multiple departments with different access requirements and security policies.

---

# Departments and Employee Count

| Department | Number of Employees |
|------------|--------------------|
| HR | 2 |
| Finance | 2 |
| IT | 3 |
| Developers | 6 |
| Management | 2 |

Total Employees: 15

---

# Naming Convention

## User Account Format

All employee accounts follow the naming convention:

firstname.deptname@nordictech.local

### Examples

- anna.hr@nordictech.local
- erik.finance@nordictech.local
- lars.it@nordictech.local
- sofia.dev@nordictech.local

---

# Security Rules

The following security policies are implemented for all employees:

## General Policies

- Multi-Factor Authentication (MFA) enabled for all users
- Strong password policy enforced
- Least privilege access model applied
- Department-based access control implemented
- Administrative access restricted to IT department
- Shared company resources monitored regularly

## Password Policy

- Minimum 12 characters
- Combination of uppercase, lowercase, numbers, and symbols
- Password expiration every 90 days
- Password reuse restricted

---

# Groups

The following groups are created to manage permissions and access control.

| Group Name | Purpose |
|------------|---------|
| HR-Team | Access to HR resources |
| Finance-Team | Access to financial resources |
| IT-Admins | Administrative privileges |
| Developers | Access to development resources |
| Managers | Access to management documents |
| All-Employees | Company-wide shared resources |

---

# Access Control Rules

| Resource | Access Permission |
|----------|------------------|
| HR Files | HR-Team only |
| Finance Files | Finance-Team only |
| Admin Portal | IT-Admins only |
| Development Resources | Developers only |
| Management Reports | Managers only |
| Shared Documents | All Employees |

---

# Project Goals

This project is designed to demonstrate practical skills in:

- Azure Administration
- Microsoft 365 Administration
- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Multi-Factor Authentication (MFA)
- IT Documentation
- Cloud Security Fundamentals
