# 📂 Modern Attack Categories

Attacks today span digital, physical, and emerging tech. Map each to IAM actions.

---

## 🔑 Password Attacks
- **Types:** Brute-force, dictionary, rainbow-table  
- **IAM Controls:**  
  - 🔒 **Strong password policies** (length, rotation)  
  - ⚡ **Rate-limiting & lockout thresholds**

---

## 🏢 Physical Attacks
- **Types:** Malicious cables, badge cloning, tailgating  
- **IAM Controls:**  
  - 🛂 **Phygital access** integration (badges + MFA)  
  - 🚪 **Physical security logs** integrated into SIEM

---

## 🚚 Supply-Chain Attacks
- **Method:** Compromise software or hardware components before delivery.  
- **IAM Controls:**  
  - 🔍 **Vendor-risk assessments** (Domain 1)  
  - 🔑 **Code-signing & attestation** in CI/CD (Domain 8)

---

## 🤖 Adversarial AI & Crypto Attacks
- **Method:** Poison ML models or downgrade crypto protocols.  
- **IAM Controls:**  
  - 🧪 **Model validation pipelines** with IAM checks  
  - 🔐 **Strong cipher suites** enforced via identity-based policies

---

> 🚀 **Insight:**  
> A comprehensive IAM program spans **all** attack categories—digital, physical, and beyond.
