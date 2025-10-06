# Information Security Risk Assessment & Control Implementation  
*Coursework Project | ITMO University, St. Petersburg*

## 📌 Overview
This academic project applies **ISO/IEC 27001, 27005, 31000, and 22301** to conduct a full information security risk assessment for **Crystal Bank**, a fictional financial institution. The work follows a structured 6-stage methodology to identify, assess, treat, and re-evaluate risks affecting critical assets.

---

## 🧩 Project Structure & Key Findings

### 1️⃣ Assets Identification & Assessment
- Identified **8 key assets**: Customer Data, Employee Records, Physical Servers, Financial Systems, Network Infrastructure, ATM Systems, Mobile Banking App, Backup Systems
- Classified by **type** (Tangible, Intangible, Digital) and assigned **owners** (CIO, CTO, HR Head, etc.)
- Scored asset value (1–10):  
  - **Customer Data**: 10 (Very High)  
  - **Mobile Banking App**: 10 (Very High)  
  - **Financial Systems**: 9 (High)

---

### 2️⃣ Vulnerabilities Identification & Assessment
- Mapped vulnerabilities to assets using **penetration testing, audits, and scans**
- Top vulnerabilities:
  - **Customer Data**: Lack of encryption (Score: 4)
  - **Financial Systems**: Software vulnerabilities (Score: 4)
  - **Mobile Banking App**: Weak authentication (Score: 4)

---

### 3️⃣ Threats Identification & Assessment
- Linked threats to vulnerabilities per **ISO 27005 Annexes C & D**
- Key threats:
  - **Customer Data** → Data Breach (External, Score: 4)
  - **Financial Systems** → Cyber Attack (External, Score: 4)
  - **Mobile App** → Account Takeover (External, Score: 4)

---

### 4️⃣ Risk Identification & Assessment
- Calculated risk = **Likelihood × Business Impact**
- Final risk levels:
  - **Mobile Banking App**: **Very High** (Likelihood: High, Impact: Very High)
  - **Financial Systems**: **High**
  - **Customer Data**: **Medium**

---

### 5️⃣ Controls Selection & Implementation
- Selected **ISO 27001 Annex A controls** for risk treatment:
  - **Financial Systems**:  
    `A.12.6.1` (Technical vulnerability management), `A.13.1.1` (Network security), `A.14.1.2` (Secure development)
  - **Mobile Banking App**:  
    `A.9.2.3` (Authentication), `A.9.4.1` (Access control), `A.14.1.2` (Secure development)

---

### 6️⃣ Residual Risk Re-Assessment
- After applying controls:
  - **Financial Systems**: Residual Risk = **Medium** → *Mitigate further*
  - **Mobile Banking App**: Residual Risk = **High** → *Mitigate immediately*

---

## 📄 Deliverable
📄 [View Full Report](louise_namugayi_risk_management_coursework.pdf)

---

## 📚 Standards & References
- ISO/IEC 27001 — Information Security Management  
- ISO/IEC 27005 — Risk Management Guidelines  
- ISO/IEC 31000 — Risk Management Principles  
- ISO/IEC 22301 — Business Continuity  
- ISO/IEC 13335 — Security Management

---

## 👤 Author
**Louise Namugayi**  
Faculty of Secure Information Technologies, ITMO University  
Supervisor: Livshitz Ilya, PhD  
Completed: April 2025

