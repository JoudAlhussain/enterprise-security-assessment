# Enterprise Security Assessment — Waffarah E-Commerce Platform

<p align="left">
  <img src="https://img.shields.io/badge/Status-In%20Progress-yellow"/>
  <img src="https://img.shields.io/badge/Type-Security%20Assessment-informational"/>
  <img src="https://img.shields.io/badge/Pillar-Governance%20%7C%20Risk%20%7C%20Technical-blueviolet"/>
</p>

| | |
|---|---|
| **Author** | Joud Alhussain |
| **Date** | Aug 2026 |
| **Methodology** | OWASP Testing Guide (OWASP Top 10 focus) |
| **Tools Used** | Nmap, Nessus, OWASP Juice Shop |
| **Report** | [PDF Report](#) |

---

## 📋 Project Overview
This project simulates a consultant-style black-box security assessment of Waffarah, a fictional mid-size e-commerce company, ahead of a compliance audit. 
The assessment identifies and validates vulnerabilities in the customer-facing web application, scores them by risk, and delivers a remediation roadmap in the same format a professional security consultancy would provide to a paying client.

## 🏢 Business Scenario
Waffarah is a mid-size e-commerce company (~150 employees) handling customer orders and payment data. Ahead of an upcoming regulatory compliance audit, Waffarah's leadership engaged an external security consultant to independently assess their web application for vulnerabilities that could expose customer data or damage the business.

## 🎯 Objectives
- Identify exploitable vulnerabilities in Waffarah's customer-facing web application
- Validate findings with evidence (not just automated scan output)
- Score each finding by likelihood and business impact
- Deliver a prioritized, business-readable remediation roadmap

## 🔍 Scope

**Client:** Waffarah — a mid-size e-commerce company (~150 employees) 
processing customer orders and payment data.

**Target of Assessment:** Waffarah's customer-facing web application 
(simulated using OWASP Juice Shop, a deliberately vulnerable app used 
here to stand in for the client's real platform).

**Testing Type:** Black-box (no prior access to source code or credentials — 
testing performed as an external, unauthenticated attacker would).

**Testing Window:** [Insert your actual start–end date

**In Scope:**
- Web application functionality (login, search, checkout, product reviews)
- API endpoints exposed by the application
- Session and authentication mechanisms

**Out of Scope:**
- Denial-of-Service (DoS) testing
- Social engineering or phishing
- Physical security testing
- Any infrastructure outside the deployed Juice Shop instance

**Authorization:** This assessment was conducted with the full knowledge 
and authorization of Waffarah  management, under a signed (fictional) 
engagement agreement, strictly for portfolio and educational purposes.

## 🧭 Methodology
This assessment follows the OWASP Testing Guide, with findings mapped against the OWASP Top 10. Testing proceeds in four stages: 
1- reconnaissance and scanning.
2- manual validation of scan results.
3- risk scoring 
4- business-impact reporting.

## 🖥️ Environment
| Component | Detail |
|---|---|
| Target | OWASP Juice Shop (Docker) — standing in for Waffarah's platform |
| Attacker system | Kali Linux |
| Network | Isolated NAT lab (host-only network, no external exposure) |

## ⚙️ Execution
A clear, chronological walkthrough of what was actually done — commands, steps, evidence captured.

## 🔎 Key Findings
| # | Finding | Severity | Category |
|---|---|---|---|
| 1 | | Critical / High / Medium / Low | |

## 💼 Business Impact
Translate the technical findings into plain business risk — cost, reputation, compliance exposure.

## ✅ Recommendations
Prioritized, actionable remediation or treatment steps, mapped to each finding above.

## 📚 Lessons Learned
What you'd do differently next time, and what this project taught you technically or professionally.

## 📎 Repository Resources
- 📄 [Full PDF Report](#)
- 💼 [LinkedIn Post](#)
- 🖼️ [Screenshots / Evidence](./evidence)

---
<p align="center"><i>Part of the <a href="https://github.com/JoudAlhussain/JoudAlhussain">Cybersecurity Professional Portfolio</a></i></p>
