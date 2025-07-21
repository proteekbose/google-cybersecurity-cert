# 🔐 CISSP’s Eight Domains

The **Certified Information Systems Security Professional (CISSP)** Common Body of Knowledge is organized into eight core domains. Below is an overview of each domain and its relevance to an IAM-centric cybersecurity practice.

---

## 1. Security & Risk Management  
- **Focus:** Governance, compliance, legal/regulatory issues, risk analysis, security policies  
- **IAM Tie-In:**  
  - Define and enforce **identity policies** (password, MFA, privileged access)  
  - Use IAM logs & metrics to feed **risk assessments** and compliance audits  

---

## 2. Asset Security  
- **Focus:** Classification, ownership, data handling requirements, privacy protection  
- **IAM Tie-In:**  
  - Leverage IAM **attribute-based policies** to enforce data classification  
  - Automate **data access revocation** when classification or ownership changes  

---

## 3. Security Architecture & Engineering  
- **Focus:** Secure system design, cryptography, single-sign-on, trusted computing base  
- **IAM Tie-In:**  
  - Design **federated identity** architectures (SAML, OAuth2/OIDC)  
  - Integrate **key-management** with IAM (encryption keys bound to user identities)  

---

## 4. Communication & Network Security  
- **Focus:** Secure network components, segmentation, VPNs, firewalls, network attacks  
- **IAM Tie-In:**  
  - Enforce **network-level authentication** (e.g., 802.1X port auth)  
  - Use IAM to control **VPN and zero-trust network access**  

---

## 5. Identity & Access Management (IAM)  
- **Focus:** Identity lifecycle, SSO, federation, administrator & service account management  
- **IAM Tie-In:**  
  - Central domain—design **RBAC/ABAC**, **MFA**, **just-in-time** admin sessions  
  - Implement **continuous authentication** and risk-based access  

---

## 6. Security Assessment & Testing  
- **Focus:** Penetration testing, vulnerability assessments, security control testing  
- **IAM Tie-In:**  
  - Validate **IAM configurations** (policy reviews, privilege reviews)  
  - Automate **permissions drift detection** and remediation testing  

---

## 7. Security Operations  
- **Focus:** Incident response, forensics, logging & monitoring, disaster recovery  
- **IAM Tie-In:**  
  - Incorporate **identity-centric alerts** into SIEM/SOAR  
  - Automate **user-centric playbooks** for account compromise and deprovisioning  

---

## 8. Software Development Security  
- **Focus:** Secure coding, DevSecOps, change management, integrity checks  
- **IAM Tie-In:**  
  - Integrate **IAM checks** in CI/CD pipelines (e.g., artifact signing, code-owner approvals)  
  - Enforce **least-privilege service accounts** for pipelines and microservices  

---

> 💡 **Reflection:**  
> The CISSP domains reinforce that **identity is the thread** woven through every aspect of cybersecurity— from policy and architecture to operations and development.
