# ConnectSphere Cybersecurity Governance Assessment

## Overview

This repository contains the cybersecurity governance assessment for **ConnectSphere**, a professional networking platform designed for user profiles, event registration, and online discussions.

The assessment reviews security weaknesses in the proposed system architecture, prioritizes risks, and documents corrective measures to improve data protection, access control, system integrity, and service availability.

## Assessment Objectives

- Identify and prioritize cybersecurity risks.
- Apply the CIA Triad and Principle of Least Privilege.
- Assess authentication, authorization, encryption, and input validation controls.
- Recommend secure software development and monitoring practices.
- Consider data protection expectations under GDPR and CCPA.
- Propose a corrected architecture with security controls.

## Deliverables

### 1. Cybersecurity Governance Review Card

Documents three key risk findings covering confidentiality, integrity, and availability, together with recommended mitigations and a monitoring metric.

### 2. Corrected Architecture Diagrams

Presents proposed architectural improvements, including HTTPS/TLS, secure API access, private databases, input validation, protected administrator access, and centralized security logging.

### 3. Summary of Review Process

Explains the risk assessment methodology, application of cybersecurity principles, compliance considerations, and the importance of security monitoring.

## Assessment Sets

**Set 1: ConnectSphere Professional Event Networking MVP**

Focuses on unencrypted HTTP traffic, exposed databases, weak administrator access, unsafe SQL queries, and missing monitoring controls.

**Set 2: ConnectSphere Professional Connection Platform V1**

Focuses on exposed frontend API keys, insecure administrator credentials, unsafe SQL queries, unrestricted email service requests, and weaknesses in forum and event data protection.

## Security Principles Applied

- **CIA Triad:** Confidentiality, Integrity, and Availability.
- **Principle of Least Privilege:** Restricting access to the minimum permissions required.
- **Secure Software Development Life Cycle (SSDLC):** Integrating security checks throughout development.
- **Input Validation:** Preventing malformed input and injection attacks.
- **Defense in Depth:** Applying multiple complementary security controls.
- **Security Monitoring:** Detecting suspicious activity through logs, metrics, and alerts.

## Repository Structure



The diagram image files are optional if the corrected architecture diagrams are available only inside the PDF.

## Scope and Limitations

This assessment is based on the supplied project brief and architecture diagrams. It identifies potential vulnerabilities and proposes defensive controls. It does not represent a penetration test, an independent technical audit, or a legal compliance certification.

GDPR and CCPA applicability depends on the relevant jurisdiction and circumstances.

## Author

**Serge Benit Igizeneza**

Cybersecurity | IT Support | Systems and Network Administration

## Disclaimer

This repository is intended for educational and defensive cybersecurity purposes. The recommendations are proposed security improvements and should be validated against the actual implementation before deployment.
