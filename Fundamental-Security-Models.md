# CORE SECURITY MODELS

# 1. CIA Triad

The CIA Triad is a foundational model in cybersecurity that defines three key objectives: Confidentiality, Integrity, and Availability. These principles guide how information and systems should be protected, and nearly every security decision or threat can be mapped to one or more of them.

# Confidentiality - means keeping data private and only accessible to authorized users.
- Ways it's enforced include encryption, authentication, access control, and user permissions.  
Examples of breaches: hacked databases, exposed credentials, or insider leaks.

# Integrity -  ensures data remains accurate, consistent, and unaltered. 
- Integrity is protected through hashing, digital signatures, checksums, and audit trails.  
Examples: altered transactions, fake logs, or injected code in trusted files.

# Availability -  means systems and information are accessible when needed.
- To maintain availability, systems use backups, failover setups, redundancy, DDoS protection, and resource monitoring.  
Examples of availability threats: server outages, DDoS attacks, hardware failure, or poor system design.


Together, they help evaluate risks, design secure systems, and respond to incidents. For example, a data breach compromises confidentiality, corrupted files affect integrity, and a denial-of-service attack targets availability. Security tools, policies, and architectures are often built around maintaining a balance between all three areas, depending on what the system handles and what’s most at risk.
---

## Why It Matters

The CIA Triad is used as a framework across all areas of security — from penetration testing and incident response to system architecture and compliance. Most attacks hit at least one part of the triad:

- A leak hits "confidentiality"
- A data tamper hits "integrity"
- A DDoS hits "availability"

It’s also used to guide what protections are most important in a given context. For example, in healthcare systems, confidentiality is a major priority. In financial services, integrity might take the lead. For emergency response systems, availability is often most critical.

Understanding the CIA Triad helps you think like both an attacker (what to break) and a defender (what to protect).
