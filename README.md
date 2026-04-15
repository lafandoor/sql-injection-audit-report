# 🛡️ SQL Injection Assessment & Security Audit Portfolio
**Conducted by:** Youssef Moataz  
**Platform:** DVWA (Infrastructure Assessment)  
**Status:** [CRITICAL] 100% Data Exfiltration Confirmed

---

## 🚀 Overview

This repository contains a high-fidelity security assessment documenting the identification, exploitation, and remediation of SQL Injection vulnerabilities. The project is designed as a professional portfolio piece, showcasing technical proficiency in vulnerability research and formal security reporting.

### 🌐 [Live Technical Dashboard](https://lafandoor.github.io/sql-injection-audit-report/)
*View the interactive "Noir" dashboard featuring terminal logs and exfiltrated credential sets.*

---

## 💎 Key Features

- **Professional Reporting:** Includes both an interactive web dashboard and a formal, printable Corporate Security Audit (PDF-Ready).
- **Automation Depth:** Full SQLMap exploitation logs showcasing multi-vector detection (UNION-based & Time-based Blind).
- **Custom Tooling:** Featured bespoke Python scanner (`sqli_scanner.py`) implementing timing analysis and heuristic-based signature matching.
- **Evidentiary Appendix:** A complete technical catalog of 25 screenshots mapping the entire attack lifecycle.
- **Credential Analysis:** Documented exfiltration and successful decryption of administrative records.

---

## 🛠️ Technical Methodology

The audit followed a multi-phased approach mirroring real-world penetration testing patterns:
1. **Reconnaissance:** Session mapping and dependency configuration.
2. **Logic Probing:** Heuristic determination through Boolean-based manual payloads.
3. **Automated Exploitation:** Deep database mapping and bulk record extraction via SQLMap.
4. **Custom Validation:** Logic verification through bespoke Python scripts.
5. **Remediation:** Implementation of Parameterized Queries (PDO) to nullify injection vectors.

---

## 📁 Project Structure

```bash
├── index.html          # Interactive Security Dashboard
├── formal_report.html  # Formal Audit Report (PDF-Ready)
├── style.css           # Custom Noir & Gold Design System
├── app.js              # Interactivity Logic
├── pics/               # Technical Evidence Gallery (25 Items)
└── Script/
    └── sqli_scanner.py # Bespoke Vulnerability Scanner logic
```

---

## 📄 Corporate Report

The [Formal Audit Document](formal_report.html) is designed for executive review.  
**To generate a PDF:** Open the file in your browser and use **Ctrl + P** (Save as PDF).

---

## ⚖️ Legal Disclaimer

This assessment was conducted in a controlled lab environment (DVWA) for educational and portfolio purposes only. Unauthorized access to computer systems is illegal and unethical.

**Portfolio of Youssef Moataz** | Security Assessment | 2026
