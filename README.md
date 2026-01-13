# 🛡️ Reconnaissance & Attack Surface Assessment (Practice Lab)

> **Type:** Learning / Practice Lab  
> **Environment:** Deliberately vulnerable or simulated target  
> **Status:** Non-production • No real-world organization  
> **Author:** Vikash Choudhary
> **Purpose:** Methodology & reporting practice

---

## 📌 Executive Summary

This repository documents a **practice reconnaissance and attack surface assessment**
performed in a controlled learning context.

The objective is **not exploitation**, but to demonstrate:
- How attackers gather information
- How uncertainty is reduced during reconnaissance
- How findings should be structured and reported professionally

> **Key idea:**  
> Reconnaissance is often the most valuable phase of an attack — long before exploitation begins.

---

## 🎯 Objectives

- Understand external attack surface discovery
- Practice DNS and web exposure analysis
- Identify technologies and platforms in use
- Think from an attacker’s perspective
- Learn how to write a clean, professional recon report

---

## 🔍 Scope & Rules

### In Scope
- Publicly accessible assets only
- DNS metadata
- HTTP/HTTPS services
- Technology fingerprinting

### Out of Scope
- Exploitation
- Credential attacks
- Brute forcing
- Denial of Service
- Testing real organizations

> ⚠️ This lab does **not** target any real company or production system.

---

## 🧠 Methodology Overview

OSINT
↓
DNS Enumeration
↓
HTTP Validation
↓
Technology Fingerprinting
↓
Analysis & Reporting


This mirrors how real-world reconnaissance is performed in a professional engagement.

---

## 🌐 Attack Surface Mapping (Conceptual)

### Assets of Interest
- Domains & subdomains
- DNS records and trust relationships
- Web entry points (login, admin, APIs)
- CMS and frameworks

### Why This Matters
Each confirmed asset:
- Reduces attacker guesswork
- Narrows exploitation paths
- Increases attack efficiency

---

## 🧱 Technology Awareness

The following categories are typically identified during recon:
- Web servers (Apache, Nginx, IIS)
- CMS platforms (WordPress, etc.)
- Backend frameworks
- Client-side technologies
- Third-party services

> Identifying **what is running** determines **what can be attacked**.

---

## 🚨 Risk Indicators (Not Vulnerabilities)

This lab focuses on **signals**, not confirmed vulnerabilities.

Examples of risk indicators:
- Public admin or login interfaces
- Identifiable CMS or plugins
- Legacy or stale DNS records
- Reused technology stacks across hosts

These indicators guide **what to test next**.

---

## 🧠 Attacker Perspective (Reflection)

### What would attackers value most?
- Confirmed alive web services
- Authentication endpoints
- CMS and framework identification
- Infrastructure patterns from DNS

### What reduces attacker effort?
- Accurate HTTP validation
- Technology fingerprinting
- Elimination of dead or false assets

---

## 🔮 What Would Be Tested Next (In a Real Engagement)

If this were a real assessment, follow-up testing would include:
- Authentication and access control testing
- CMS vulnerability validation
- Subdomain takeover analysis
- API authorization checks

---

## 🧾 Tools (Listed for Transparency)

> Tools are listed for completeness — **not as a measure of skill**

- Amass
- dnsx
- dig / nslookup
- httpx
- Wappalyzer
- WhatWeb
- WPScan (passive mode)

---

## 📎 Limitations

- Practice environment only
- No exploitation performed
- No authenticated access
- Snapshot-in-time analysis

---

## 🏁 Conclusion

This lab demonstrates that effective reconnaissance is less about tools
and more about **thinking clearly, prioritizing attacker value,
and communicating findings effectively**.

> Good security starts with understanding what information is already exposed.

---

## 📚 References

- OWASP Web Security Testing Guide  
- OWASP Top 10  
- NIST SP 800-115  
- MITRE ATT&CK (conceptual alignment)

---

## ⚠️ Ethical Notice

This repository is for **educational purposes only**.  
No real-world systems were tested, harmed, or targeted.
