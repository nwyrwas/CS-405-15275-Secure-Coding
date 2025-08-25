# CS-405-15275-Secure-Coding

# 🛡️ Green Pace Security Policy Project  

## 📌 Project Overview  
This repository contains the complete deliverables for **CS-405: Secure Coding** Project Two. The project centers on the design, documentation, and presentation of a **comprehensive security policy** for *Green Pace*, a fictional software development company.  

The goal of this project was to learn how to design security policies that integrate **coding standards, risk analysis, encryption, authentication and authorization controls (AAA), and automation within a DevSecOps pipeline**. By completing this work, I strengthened my ability to design systems that are not just functional, but also **secure by design**, aligning with modern software engineering practices.  

---

## 📂 Repository Contents  

### 🔸 Security Policy Document  
- **CS 405 Security Policy Template.docx**:contentReference[oaicite:0]{index=0}  
  - Full written **Green Pace Secure Development Policy**.  
  - Includes:  
    - **Overview, Purpose, and Scope** of the policy.  
    - **Ten Core Security Principles**, such as validating input, least privilege, defense in depth, and simplicity.  
    - **Ten Secure Coding Standards (CERT C/C++)** mapped to principles, with compliant and noncompliant code examples.  
    - **Risk Assessment Tables** ranking vulnerabilities by severity, likelihood, and remediation cost.  
    - **Automated Detection Tools** (Clang, Coverity, CodeSonar, Astree, Cppcheck, Axivion) linked to each coding standard.  
    - **Encryption Policies** (data at rest, in flight, and in use) with AES-256, TLS/IPSec, and secure enclaves.  
    - **Triple-A Framework (Authentication, Authorization, Accounting)** with role-based access controls and logging.  
    - **Audit Controls, Enforcement, and Exceptions Process** for governance.  
    - **Policy Version History** documenting revisions and improvements.  

---

### 🔸 Presentation Materials  
- **CS 405 Project Two Presentation Template.pptx**:contentReference[oaicite:1]{index=1}  
  - A slide deck summarizing the Green Pace Security Policy.  
  - Covers defense-in-depth, guiding principles, coding standards, threat matrix, encryption, AAA, automation, risks/benefits, and recommendations.  
  - Designed for stakeholders to understand the **value of proactive, standards-based security**.  

- **CS 405 Project Two Script Template.docx**:contentReference[oaicite:2]{index=2}  
  - Full presentation script with detailed speaker notes.  
  - Provides **narrative context** to walk through the policy and its enforcement strategies.  
  - Ensures clarity when presenting complex topics like **automation pipelines** or **encryption-in-use** to non-technical audiences.  

---

### 🔸 Reflection and Portfolio Material  
- **8-2 Journal Portfolio Reflection.docx**:contentReference[oaicite:3]{index=3}  
  - A written reflection on course takeaways and professional growth.  
  - Emphasizes:  
    - The importance of designing **security policies early in the SDLC** (“secure by design”).  
    - How **Zero Trust principles** eliminate implicit trust and enforce constant validation.  
    - The need to **balance risk vs. cost of mitigation** when applying policies.  
    - The role of **threat intelligence and continuous monitoring** in adapting to evolving risks.  
    - A shift in perspective from focusing solely on **functionality and performance** to integrating **security and resilience** as primary goals.  

---

## 🧠 Key Skills and Lessons Learned  

This project was more than just writing a policy — it was a **hands-on experience in security engineering**.  

### 🔹 Secure by Design  
- Learned that **security must be integrated from the start**, not bolted on at the end.  
- Practiced embedding secure coding standards (CERT C/C++) into the development lifecycle.  
- Understood how small issues like buffer overreads (STR32-C) or integer conversions (INT31-C) can escalate into major exploits.  

### 🔹 Risk Assessment and Prioritization  
- Developed a **Threat Matrix** ranking vulnerabilities by severity, likelihood, and remediation cost:contentReference[oaicite:4]{index=4}.  
- Learned to **prioritize fixes**: High-risk vulnerabilities must be addressed immediately, while low-risk issues can be deferred strategically to manage technical debt.  
- Gained experience balancing **business constraints** with **security needs** (cost-benefit tradeoffs).  

### 🔹 Encryption Policies  
- Implemented **AES-256 encryption** for data at rest.  
- Applied **TLS/IPSec protocols** for encryption in flight.  
- Studied emerging techniques like **encryption-in-use** (secure enclaves, homomorphic encryption) for protecting data being processed:contentReference[oaicite:5]{index=5}.  
- Learned how to **write practical encryption policies** that define not only technology, but also when, where, and why encryption should be applied.  

### 🔹 AAA (Authentication, Authorization, Accounting)  
- Learned how to enforce **Authentication** using MFA and identity checks.  
- Designed **Authorization policies** with least-privilege and role-based access control (RBAC).  
- Emphasized **Accounting and logging** as critical to audits, compliance, and detecting insider threats.  

### 🔹 DevSecOps and Automation  
- Built understanding of **security automation** across the SDLC.  
- Integrated **Clang warnings, static analysis (CodeSonar, Coverity, Axivion), and formal analysis (Astree, ÉCLAIR)** directly into CI/CD pipelines:contentReference[oaicite:6]{index=6}.  
- Automated unit testing, regression testing, and dependency scanning to ensure every code commit was validated.  
- Learned that automation reduces human error, ensures repeatability, and enforces security at scale.  

### 🔹 Zero Trust Model  
- Adopted the mindset that **no user, device, or network should be trusted by default**.  
- Understood how Zero Trust strengthens defense against insider threats, lateral movement, and misconfigurations.  
- Realized that **continuous validation** is more reliable than perimeter defenses.  

### 🔹 Professional Skills  
- Practiced **communicating technical policies** to both technical and non-technical audiences.  
- Built **formal documentation** (policies, risk assessments, automation strategies).  
- Developed **presentation and storytelling skills** through the script and slide deck.  
- Gained confidence in **tying principles (like least privilege) to standards (like DCL51-CPP or MEM54-CPP)**, demonstrating that security decisions are grounded in best practices.  

---

## 🌟 Portfolio Reflection  

This project highlights my ability to:  
- Develop a **comprehensive security policy** aligned with industry standards.  
- Apply **secure coding practices** across C/C++ development.  
- Conduct **threat modeling and risk assessment** with prioritization frameworks.  
- Implement **encryption policies** for data at rest, in flight, and in use.  
- Enforce **AAA controls** (authentication, authorization, accounting).  
- Integrate **automation into DevSecOps pipelines** for continuous enforcement.  
- Communicate complex security concepts clearly through **presentations and documentation**.  

It demonstrates not only technical skills but also:  
- **Critical thinking** in risk prioritization.  
- **Problem-solving** in mapping coding standards to principles.  
- **Professional communication** in producing policies, presentations, and reflections.  

This project serves as a **capstone portfolio artifact**, showcasing my readiness to contribute to professional security engineering practices.  
