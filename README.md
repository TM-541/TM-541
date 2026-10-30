<p align="center">
  <img src="assets/banner.svg" alt="Muhammad Talha: AI Security Engineer, Cybersecurity. I build AI systems that can't be talked into misbehaving, and I prove it with tests, threat models and evidence." width="100%">
</p>

<p align="center">
  <a href="https://tm-541.github.io/Portfolio/"><img src="https://img.shields.io/badge/Portfolio-tm--541.github.io%2FPortfolio-2ee6c5?style=for-the-badge&labelColor=05070d" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/muhammadtalha-cybersecurity"><img src="https://img.shields.io/badge/LinkedIn-Connect-4da3ff?style=for-the-badge&labelColor=05070d" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/IEEE-IBCAST_2026-2ee6c5?style=for-the-badge&labelColor=05070d" alt="IEEE IBCAST 2026">
</p>

---

### `> whoami`

**Cybersecurity engineer focused on AI security.** I hold a **BS in Cyber Security** from Air University, Islamabad (2022–2026) and I'm completing an **MS in Cyber Security** there, while working as an **AI Engineer Intern at Tekdex**.

I work where AI and security meet: hardening LLM applications against prompt injection, building detection pipelines where the AI *interprets* findings but never decides them, and securing edge networks with cryptography and on-device intrusion detection. I approach it with a governance mindset (ISO/IEC 27001, risk, compliance).

```text
core      → AI & LLM security: prompt-injection defence · secure RAG · LLM output validation
strands   → Detection engineering & SOC · GRC / ISO 27001 · Secure IoT & wireless
research  → Edge-AI intrusion detection over LoRa (IEEE IBCAST 2026, conditionally accepted)
```

---

### `> ls ./featured`

<table>
<tr>
<td width="50%" valign="top">

#### 🛡️ [AEGISINTEL](https://github.com/TM-541/AEGISINTEL)
**Evidence-first SOC investigation & threat-intelligence platform.**

Deterministic rules and statistics produce findings, and a local LLM only *interprets* them. Its output is validated in code.

- 3 detection layers: Sigma subset · correlation · behavioural analytics
- Validated MITRE ATT&CK mapping
- Argon2id + RBAC; two-person approval; hash-chained audit log
- **290 tests** · ruff · mypy · Bandit (0 open issues)

`Python` `Streamlit` `SQLite` `Ollama` `Sigma` `ATT&CK`

</td>
<td width="50%" valign="top">

#### 🔐 [Secure Policy RAG Assistant](https://github.com/TM-541/AI-Secure-Policy-RAG-Assistant)
**Prompt-injection-hardened, fully local RAG assistant.**

Answers questions from policy documents with citations. Every request must pass **7 independent defence layers**.

- De-obfuscation (Unicode, leetspeak, Base64, ROT13, hex)
- Relevance gate · canary-token leak detection
- PII and link redaction · hashed audit trail
- Red-team test suite + pip-audit in CI

`Python` `Ollama` `ChromaDB` `SQLite` `Streamlit`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### 📡 [AEGIS-LN](https://github.com/TM-541/AEGIS-LN): AI-Protected LoRa Mesh *(final-year project · research)*
A decentralised LoRa mesh with **AOMDV** multipath routing, **ECDH** key exchange, **AES-128-CBC** encryption and **HMAC-SHA256** authentication, plus autoencoder and deep-packet-inspection anomaly detection with a real-time threat dashboard. Basis of my IEEE IBCAST 2026 paper. *Source code is private while the research is under publication.*

`ESP32-S3` `LoRa` `C++` `Python` `mbedTLS` `Autoencoders`

</td>
</tr>
</table>

---

### `> cat research.md`

| | |
|---|---|
| 📄 **IEEE IBCAST 2026** *(conditionally accepted)* | *Hardware-Isolated Secure Mesh Communication with Edge-AI Intrusion Detection over LoRa* (co-author) |
| 🌐 **International grant proposal** *(under review)* | Pakistan–Sri Lanka proposal: ML-driven intrusion detection & secure DTN LoRa for disaster-resilient networks |

---

### `> history | tail`

| Period | Role | Organisation |
|---|---|---|
| Sep 2026 – Present | **AI Engineer Intern** | Tekdex Inc. |
| Jul 2026 – Sep 2026 | Trainee Engineer, Systems & IoT | WaveLink Technologies |
| Jan 2026 – Jul 2026 | **Cyber Security R&D Intern** | Tech Quadrant |
| Feb 2026 – Apr 2026 | Cyber Security Instructor & Operations Lead | Yuni |
| Aug 2025 – Sep 2025 | **Digital Forensics Intern** | Cyborts |
| Aug 2024 – Dec 2025 | Operations & Compliance Coordinator | TM Engineering |

<details>
<summary><b>🎓 Education</b></summary>
<br>

| | |
|---|---|
| **MS Cyber Security** | Air University, Islamabad · 2026 – Present |
| **BS Cyber Security** | Air University, Islamabad · 2022 – 2026 |
| FSc Pre-Engineering | FBISE · 2019 – 2021 |

</details>

<details>
<summary><b>📜 Certifications</b></summary>
<br>

| Credential | Issuer | Year |
|---|---|---|
| **CAISR**: Certified Artificial Intelligence Security & Risk | Red Team Leaders | 2026 |
| Certified AI-Data Security Specialist | | 2026 |
| **CSEDP**: Certified Social Engineering Defense Practitioner | The SecOps Group | 2026 |
| **ISO/IEC 27001:2022** Information Security Management Systems | SkillFront | 2025 |
| **CCEP**: Certified Cybersecurity Educator Professional | Red Team Leaders | 2025 |
| **ICIP**: Introduction to Critical Infrastructure Protection | OPSWAT Academy | 2025 |

</details>

---

### `> cat toolkit.txt`

<p>
  <img src="https://img.shields.io/badge/Python-0b111e?style=flat-square&logo=python&logoColor=2ee6c5" alt="Python">
  <img src="https://img.shields.io/badge/C++-0b111e?style=flat-square&logo=cplusplus&logoColor=2ee6c5" alt="C++">
  <img src="https://img.shields.io/badge/SQL-0b111e?style=flat-square&logo=sqlite&logoColor=2ee6c5" alt="SQL">
  <img src="https://img.shields.io/badge/Ollama-0b111e?style=flat-square&logo=ollama&logoColor=2ee6c5" alt="Ollama">
  <img src="https://img.shields.io/badge/Streamlit-0b111e?style=flat-square&logo=streamlit&logoColor=2ee6c5" alt="Streamlit">
  <img src="https://img.shields.io/badge/MITRE_ATT%26CK-0b111e?style=flat-square&logoColor=2ee6c5" alt="MITRE ATT&CK">
  <img src="https://img.shields.io/badge/Sigma-0b111e?style=flat-square" alt="Sigma">
  <img src="https://img.shields.io/badge/ISO%2FIEC_27001-0b111e?style=flat-square" alt="ISO/IEC 27001">
  <img src="https://img.shields.io/badge/ESP32-0b111e?style=flat-square&logo=espressif&logoColor=2ee6c5" alt="ESP32">
  <img src="https://img.shields.io/badge/LoRa-0b111e?style=flat-square" alt="LoRa">
  <img src="https://img.shields.io/badge/mbedTLS-0b111e?style=flat-square" alt="mbedTLS">
  <img src="https://img.shields.io/badge/GitHub_Actions-0b111e?style=flat-square&logo=githubactions&logoColor=2ee6c5" alt="GitHub Actions">
</p>

**Security:** threat modelling · vulnerability & risk assessment · detection engineering · DFIR · secure protocol design · cryptography (ECDH, AES, HMAC-SHA256, Argon2id)

---

<p align="center">
  <b>Open to AI Security, Cybersecurity, InfoSec & GRC roles.</b><br>
  <a href="https://tm-541.github.io/Portfolio/">Portfolio</a> · <a href="https://www.linkedin.com/in/muhammadtalha-cybersecurity">LinkedIn</a>
</p>
