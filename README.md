# C3-GRC

**CrochetCrochetCrochet (C3)** is a fictional SaaS company offering **Crochet as a Service**. Subscribers pay a monthly fee to access:

- Pattern libraries  
- Live virtual instruction sessions  
- A community forum  

The platform stores **customer PII (names, emails, payment information)** and runs on **AWS cloud infrastructure**. The company operates with a **small internal team of 16 employees**, making it a realistic example of a **small-to-mid size SaaS organization**.

This repository simulates a **real-world Governance, Risk, and Compliance (GRC) engagement** for C3. The goal is to design the types of artifacts a GRC analyst or security consultant would build when assessing an organization’s security posture and compliance readiness.

Project inspiration from:  
https://artempolynko.com/blog/7-grc-analyst-hands-on-projects/

> **Note:** This project is a **work in progress** and will continue evolving as additional GRC artifacts, automation, and analysis are added.

---

# Project Goals

The purpose of this project is to simulate the early stages of a **security compliance engagement** for a small SaaS company. The focus is on building foundational governance artifacts commonly used in security programs.

Key goals include:

- Creating a structured **asset inventory**
- Mapping security controls to **industry frameworks**
- Performing a **gap analysis**
- Identifying **risk and remediation priorities**
- Documenting **control ownership and evidence**

Current framework alignment focuses on:

- **ISO 27001:2022**
- **NIST SP 800-53**

---

# Work Completed So Far

## Simulated Organization Design

- Designed a fictional SaaS company environment to simulate a realistic GRC engagement
- Modeled a **16-person organization with an AWS-hosted platform**
- Documented **42 assets** across infrastructure, SaaS tools, and employee endpoints

---

## Asset Inventory

Built and maintained a centralized asset inventory including:

- Asset type and ownership
- Cloud infrastructure resources
- SaaS platforms
- Employee devices

Security attributes tracked include:

- Data classification
- PII / PCI flags
- Sensitivity scoring
- System owners and custodians

---

## Security Control Mapping

Developed a **control matrix** aligning internal controls with major security frameworks.

Current scope:

- **25 mapped controls**
- Framework mappings to **ISO 27001:2022** and **NIST 800-53**
- Control ownership assignments
- Maturity scoring
- Evidence documentation

---

## Gap Analysis

Conducted a high-level compliance assessment to identify security gaps.

Outputs include:

- Missing or partially implemented controls
- Remediation recommendations
- Prioritized improvements based on risk

This analysis simulates the type of deliverable created during a **GRC consulting engagement or internal security audit**.

---

# Repository Structure

C3-GRC/
│
├── Asset_Inventory.csv
├── Control_Matrix_Mapping.csv
├── Gap_Analysis.csv
│
└── README.md


Each file represents a key governance artifact commonly used in security and compliance programs.

---

# Planned Improvements

This project will continue expanding to simulate a more mature GRC environment.

Planned additions include:

- Risk register
- Policy library
- Security control testing procedures
- Automated compliance analysis using Python
- Dashboards for control coverage and risk tracking

---

# Why This Project Exists

Many cybersecurity portfolio projects focus heavily on **technical security tools**, but real-world security programs rely heavily on **governance and compliance processes**.

This project demonstrates practical experience with:

- Asset management
- Security control frameworks
- Compliance assessments
- Security documentation
- Risk prioritization

These are core responsibilities for roles such as:

- GRC Analyst  
- Security Consultant  
- Risk Analyst  
- Compliance Specialist  