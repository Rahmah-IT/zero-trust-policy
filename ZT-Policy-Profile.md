# Zero Trust Policy Profile

## 1. ZTA Component Definitions

### Policy Engine (PE)
The Policy Engine is the decision-maker of the Zero Trust system. It evaluates different security signals such as user identity, device security, and network conditions before deciding whether access should be allowed or denied.

### Policy Administrator (PA)
The Policy Administrator acts on the decision made by the Policy Engine. It communicates the decision and prepares the system to allow or block access based on the security rules.

### Policy Enforcement Point (PEP)
The Policy Enforcement Point is the gatekeeper that enforces the decision. It either allows or denies access to the requested resource based on the instructions received.

---

## 2. Core Principle Application

Chosen Principle: Verify Explicitly

In this scenario, the Policy Engine verifies the user's identity before granting access to the HR employee database. For example, when an employee attempts to access sensitive information, the system checks their login credentials and confirms their identity through authentication. Access is granted only after successful verification.

---

## 3. Simplified Policy Table

| Policy Requirement (Signal) | Condition to be Met by User | Action if Condition is Met |
|-----------------------------|-----------------------------|----------------------------|
| User Identity | Verified login credentials | Grant Access |
| Device Posture | Device has updated antivirus and security patches | Grant Access |
| Network Context | User is connected to a secure internal network | Grant Access |

---

## 4. Git Repository Metadata

Project: Lab 6 - Zero Trust Policy  
Filename: ZT-Policy-Profile.md  
Commit Message: Added Zero Trust Policy Profile  
GitHub URL: https://github.com/Rahmah-IT/zero-trust-policy  
Due Date: March 2, 2026 
