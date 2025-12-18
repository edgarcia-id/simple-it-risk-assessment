# simple-it-risk-assessment
A web-based tool to identify, analyze, and evaluate IT risks based on ISO 27005 concepts. Calculate Risk Score (Likelihood x Impact) and export to CSV.

# Simple IT Risk Assessment Tool 🛡️

**A lightweight, web-based tool to conduct quantitative IT Risk Assessments based on ISO 27005 concepts.**

Live Demo: [https://edgarcia-id.github.io/simple-it-risk-assessment/]((https://edgarcia-id.github.io/simple-it-risk-assessment/))

### 🧐 Why use this tool?
Managing IT Risks shouldn't always require expensive GRC software. For SMEs or initial audits, a simple matrix is often enough.
This tool helps IT Managers to:
1.  **Identify Assets** and their corresponding threats.
2.  **Calculate Risk Score** automatically (Likelihood x Impact).
3.  **Visualize Priorities** (High/Medium/Low).
4.  **Export to CSV** for reporting.

### 📐 How it works (The Matrix)
The risk score is calculated using a standard 5x5 matrix:
* **Likelihood (1-5):** From "Rare" to "Certain".
* **Impact (1-5):** From "Negligible" to "Catastrophic".
* **Formula:** `Score = Likelihood * Impact`

| Score | Level | Action |
| :--- | :--- | :--- |
| 15 - 25 | 🔴 **HIGH** | Immediate mitigation required. |
| 5 - 12 | 🟡 **MEDIUM** | Monitor and mitigate if budget allows. |
| 1 - 4 | 🟢 **LOW** | Accept risk. |

### 🛠️ Tech Stack
* HTML5 & Bootstrap 5
* Vanilla JavaScript (No backend required)
* Client-side CSV Export

---
**Maintained by:** Ed Garcia - [NusaIT.com](https://nusait.com)
*Need a full IT Audit or ISO 27001 Consultation? [Contact Me](https://nusait.com/contact)*
