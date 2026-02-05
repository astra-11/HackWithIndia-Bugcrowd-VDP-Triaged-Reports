# 🔐 HackWithIndia × Bugcrowd — Triaged Security Findings  

**Researcher:** Sharvari Dubey (Astra)
**Program:** HackWithIndia Vulnerability Disclosure Compliance Engagement (Bugcrowd)  
**Status:** 4 reports **Triaged**  
**Impact Tier:** P1, P1, P2, P3  
**Leaderboard Rank:** 🏅 **67th**  
**Special Recognition:** 🎁 **1 month of Caido Premium**  

---

## 🚀 Overview  

As part of the **HackWithIndia Vulnerability Disclosure Program on Bugcrowd**, I conducted in-depth security testing across the HackWithIndia authentication and API ecosystem. The assessment focused on trust boundaries, identity management, and error handling.

Out of **7 total submissions**, **4 high-quality findings were triaged**, reflecting meaningful security risk and real-world exploitability:

| Severity | Count | Status |
|---------|-------|--------|
| **P1 (Critical)** | 2 | Triaged ✅ |
| **P2 (High)** | 1 | Triaged ✅ |
| **P3 (Medium)** | 1 | Triaged ✅ |

These findings collectively demonstrate systemic weaknesses in:
- JWT handling and key management  
- Authentication logic  
- API exception handling  
- Error transparency  
- Session trust models  

---

## 🎯 Triaged Reports (Summary)

### 🔴 **P1 — Critical**
1. **JWT Secret Exposure → Token Forgery & Privilege Escalation**  
2. **Critical Information Disclosure via Debug Stack Traces**

### 🟠 **P2 — High**
3. **Sensitive Information Disclosure via Unhandled Exception in Workforce Export API**

### 🟡 **P3 — Medium**
4. **MFA Bypass + JWT Forgery Leading to Authentication & Authorization Compromise**

Each report in this repository contains:
- Clear vulnerability description  
- Affected endpoints  
- Step-by-step reproduction  
- Proof-of-concept evidence  
- Business impact  
- Mitigation guidance  

---

## 🧠 What “Triaged” Means on Bugcrowd  

A **Triaged** status indicates that:
- The report has been reviewed by Bugcrowd and HackWithIndia  
- The issue is considered technically valid for further assessment  
- The program is actively investigating impact and remediation  
- Additional clarifications may be requested  

This is a strong validation of research quality.

---

## 🏆 Recognition  

Ranking **67th on the leaderboard** reflects consistent, high-impact security research.  

A special thanks to **Caido** for awarding **1 month of Caido Premium**, which significantly enhanced analysis, visualization, and workflow during this engagement.

---

## 🛠️ Tools Used  

- Burp Suite  
- JWT.io  
- Hashcat  
- Kali Linux  
- Browser DevTools   
- **Caido (post-reward)**  

---

## 🎯 Scope (Primary Targets)

- `accounts.hackwithindia.com`  
- `api.hackwithindia.com`
- `hr.hackwithindia.com`  

---

## 📬 Connect  

- **GitHub:** [astra-11](https://github.com/astra-11)
- **LinkedIn:** [Sharvari-Dubey](https://www.linkedin.com/in/sharvari-dubey-806717227/)
- **Email:** astrasec11@gmail.com  

Responsible disclosure strengthens systems — and careers. 🔐  
