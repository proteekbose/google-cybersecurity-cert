# 🎣 Phishing Variants

Phishing has evolved into multiple specialized attacks. Understanding each helps tailor IAM defenses.

---

## ✉️ Business Email Compromise (BEC)
- **What:** Spoofed emails impersonating executives or vendors.  
- **Goal:** Trick finance teams into fraudulent wire transfers.  
- **IAM Defense:**  
  - 🔐 **Adaptive MFA** on high-risk users  
  - 📊 **Anomaly alerts** for unusual payment approvals

---

## 🎯 Spear-Phishing & Whaling
- **What:** Highly targeted emails to specific employees or C-suite members.  
- **Goal:** Harvest credentials or deliver tailored malware.  
- **IAM Defense:**  
  - 📧 **Email authentication** (SPF/DKIM)  
  - 🛠️ **Phish-resistant MFA** (FIDO2, security keys)

---

## 📞 Vishing & 📱 Smishing
- **Vishing:** Voice phishing via fake calls (e.g., IT help-desk).  
- **Smishing:** SMS/text-based phishing with malicious links.  
- **IAM Defense:**  
  - 🆔 **Out-of-band MFA** (separate channel)  
  - 🚨 **Phishing-simulation training** (Domain 8)

---

> 🔒 **Key Insight:**  
> No single control blocks every variant—layered IAM (conditional access + continuous auth) is essential.
