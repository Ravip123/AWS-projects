# AWS Secure Infrastructure Project
# AWS Secure Infrastructure & Security Monitoring Project

This project demonstrates how to secure AWS infrastructure, detect threats, and perform incident response using AWS native security services.

---

## 🎯 Project Goals
- Build secure AWS environment
- Detect suspicious / malicious activities
- Investigate & analyze security events
- Create incident response workflow
- Practice SOC style monitoring in AWS

---

## 🏗️ Architecture / Components Used

### 🔐 Core Security Services
- AWS GuardDuty → Threat detection
- AWS Macie → Sensitive data protection (PII detection)
- AWS Security Hub → Centralized security posture view
- AWS IAM Best Practices → Least privilege / MFA / Policies
- AWS CloudTrail → User activity logging & investigation
- VPC Flow Logs → Network traffic monitoring
- AWS CloudWatch Logs → Log storage & alerts
- AWS Config → Compliance tracking

---

## 🧠 What This Project Demonstrates

### ✅ 1. Threat Detection
Configured and tested:
- Unauthorized access alerts
- Suspicious API calls
- IAM abuse attempts
- Malicious IP communication
- Data exfiltration patterns

---

### ✅ 2. Log Analysis & Investigation
Performed investigation on:
- CloudTrail logs
- GuardDuty Findings
- VPC Flow Logs

Key focus areas:
- Who performed action?
- From where?
- Is the behavior normal?
- What’s the impact?
- Remediation steps?

---

### ✅ 3. Automation Concept
Designed approach for:
- Auto-remediation ideas
- Notifications
- Security workflow

Example automations (conceptual):
- Auto isolate compromised instance
- Send alerts to SNS / Email
- Block malicious IP
- Disable suspicious access keys

---

## 🧩 Sample Use Case Scenarios Covered
- Unauthorized IAM login attempt
- EC2 communicating with blacklisted IP
- Public S3 bucket security risk
- CloudTrail unusual activity investigation
- PII detection via Macie

---

## 🧾 Documentation
This folder contains:
- Architecture explanation
- Service wise notes
- Investigation steps
- Example findings explanation

---

## 🚀 Learning Outcome
Through this project I strengthened knowledge in:

✔ AWS security services  
✔ Threat detection mindset  
✔ SOC / Incident response approach  
✔ AWS logging and monitoring  
✔ Security architecture thinking  

---

More enhancements will be added soon including automation scripts and diagrams.
