# 🛡️ Security Frameworks – Summary & Notes

This file summarizes major cybersecurity frameworks and standards relevant to GRC, compliance, identity, and cloud security.

---

## 📦 Index

- [1. GCR – Google Cloud Risk & Compliance](#1-gcr--google-cloud-risk--compliance)
- [2. ISO/IEC 27001 – Information Security Management](#2-isoiec-27001--information-security-management)
- [3. NIST 800-53 – Security & Privacy Controls](#3-nist-800-53--security--privacy-controls)
- [4. NIST 800-63B – Digital Identity Guidelines](#4-nist-800-63b--digital-identity-guidelines)
- [5. Takeaways / Notes](#5-takeaways--notes)

---

## 1. GCR – Google Cloud Risk & Compliance

> **What it is:**  
Google’s internal security, compliance, and risk framework to meet global standards (ISO 27001, GDPR, HIPAA, FedRAMP, etc).

> **Key Concepts:**
- Shared responsibility model for cloud
- Risk mitigation for cloud users
- Alignment with NIST 800-53, ISO, and more
- Security whitepapers, audit reports, and compliance mappings

> **What I learned:**
- You need to know *where* your responsibility ends as a customer (e.g., data classification, access control) vs what GCP secures.
- Helps when deploying apps that must meet compliance (HIPAA, PCI-DSS, etc.)

---

## 2. ISO/IEC 27001 – Information Security Management

> **What it is:**  
An international standard for establishing and managing an **Information Security Management System (ISMS)**.

> **Core Elements:**
- Risk Assessment → Risk Treatment → Controls
- 93 controls in ISO 27001:2022 (used to be 114)
- PDCA cycle (Plan-Do-Check-Act)
- Statement of Applicability (SoA)

> **What I learned:**
- ISO 27001 is **risk-driven**, not checklist-based.
- Useful for securing a company at the policy/process level.
- You have to justify why you're applying or *not* applying certain controls.

---

## 3. NIST 800-53 – Security & Privacy Controls

> **What it is:**  
A comprehensive U.S. government standard for security and privacy controls across federal systems.

> **Structure:**
- Control Families (e.g., Access Control, Audit & Accountability, Incident Response)
- Control Baselines: LOW / MODERATE / HIGH
- Supports tailoring per organization or system

> **What I learned:**
- Very customizable, good reference for any security project.
- Can use the controls even in private sector — especially cloud or SaaS.
- Mapped to other standards (ISO, FedRAMP, etc.)

---

## 4. NIST 800-63B – Digital Identity Guidelines

> **What it is:**  
Covers how to **securely verify identity** and enforce **authentication**.

> **Highlights:**
- AALs (Authentication Assurance Levels): AAL1, AAL2, AAL3
- MFA guidance: SMS-based MFA discouraged, hardware token preferred
- Long passphrases > complex passwords
- Covers biometrics, OTPs, device binding, etc.

> **What I learned:**
- Encourages usability along with security
- Good resource for building secure login systems
- Surprised to learn that *password complexity rules* (like special characters) are not recommended!

---

## 5. Takeaways / Notes

- 🔐 **ISO 27001** is about management systems and policy.
- ⚙️ **NIST 800-53** is about control implementation and security architecture.
- 🔑 **NIST 800-63B** is focused entirely on login/authentication systems.
- ☁️ **GCR** is about applying these in a **cloud provider** context.

> My biggest realization:
> > "Security isn’t just tools or hardening — it’s policy, accountability, and design choices based on **risk**."

---

## 📌 Next Steps

- Apply ISO 27001 risk assessment model to a small project.
- Compare AAL2 vs AAL3 authentication methods in real apps.
- Use GCR mapping when deploying workloads on GCP.
