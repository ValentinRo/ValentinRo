<h1 align="center">Valentin · ValentinRo</h1>
<p align="center">
  <b>Bug Bounty Hunter & Web Penetration Tester</b><br>
  Authentication · Access Control · Business Logic
</p>

<p align="center">
  <a href="https://cyberscut.ro"><img src="https://img.shields.io/badge/Website-cyberscut.ro-0d1117?style=flat-square&logo=firefoxbrowser&logoColor=white" alt="Website"></a>
  <a href="https://hackerone.com/HANDLE"><img src="https://img.shields.io/badge/HackerOne-HANDLE-494649?style=flat-square&logo=hackerone&logoColor=white" alt="HackerOne"></a>
  <a href="https://bugcrowd.com/HANDLE"><img src="https://img.shields.io/badge/Bugcrowd-HANDLE-F26822?style=flat-square&logo=bugcrowd&logoColor=white" alt="Bugcrowd"></a>
  <a href="https://www.linkedin.com/in/HANDLE"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:EMAIL"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### 🎯 What I hunt

I focus on the bugs automated scanners miss — flaws that live in how an application *decides who is allowed to do what*.

- **IDOR / BOLA** — read, write, destructive and multi-tenant object access
- **Account Takeover** — password reset, magic links, OAuth account linking, session handling
- **OAuth & CSRF** — `state` handling, redirect URI validation, linking flows
- **Access-control bypass** — header, HTTP-method and Referer-based authorization gaps
- **Business logic** — checkout, pricing, coupons and order workflows (WooCommerce, e-commerce)
- **SSRF & information disclosure** — internal endpoints, PII exposure

### 🛠 Tooling I build

| Project | Description | Status |
|---|---|---|
| **AuthHunter** | Modular Python framework that turns real-world bug bounty patterns into reusable detectors for auth and access-control flaws, built around a `DETECTOR_REGISTRY` architecture | 🔒 In development |
| **Recon Ledger** | Structured catalog of recon and hunting patterns distilled from disclosed reports — each entry maps the feature, the developer's wrong assumption, and how to verify it | 🔒 Private |
| **Burp → Report pipeline** | Converts Burp Suite XML exports into structured audit reports with Critical / High / Medium / Low severity | 🔒 Private |

### 🧪 Methodology

```text
Recon  →  Map functionality  →  Find the wrong assumption  →  Verify manually  →  Prove impact  →  Report clearly
```

Every finding is verified by hand and reported with clear reproduction steps, real impact, and a concrete fix.

### 🧰 Toolbox

![Burp Suite](https://img.shields.io/badge/Burp_Suite_Pro-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Caido](https://img.shields.io/badge/Caido-1E1E2E?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=flat-square&logo=woocommerce&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

Burp extensions in daily use: Autorize · Auth Analyzer · DOM Invader · Collaborator · JS Miner · Logger++

### 📝 Write-ups

Write-ups are published on [cyberscut.ro/blog](https://cyberscut.ro/blog.html) **only after** the issue is fixed and disclosure is permitted by the program or client.

<!-- Add entries as they are published:
- [Title](link) — vulnerability class · severity · date
-->

### 📚 Learning

- PortSwigger Web Security Academy — <!-- progress -->
- <!-- certifications -->

### 🤝 Responsible disclosure

I test only in-scope assets of public bug bounty programs, or systems whose owners have given written authorization. No data is kept, shared, or used beyond what is needed to demonstrate impact.

---

<p align="center"><sub>Based in Romania 🇷🇴 · Open to security audits and pentest engagements for SMBs</sub></p>
