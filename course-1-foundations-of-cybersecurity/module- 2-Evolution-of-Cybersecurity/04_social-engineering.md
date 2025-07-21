# 🎭 Social Engineering

Human trust is often the weakest link. Recognize tactics to strengthen IAM-guided defenses.

---

## 🔌 USB Baiting
- **Method:** Leave infected USB sticks in public areas.  
- **Result:** Curious users plug in, executing malware.  
- **Defense:**  
  - 🚫 **Disable USB autorun** via group policy  
  - 🛂 **Endpoint control** for removable media

---

## 🌊 Watering-Hole Attacks
- **Method:** Compromise websites frequented by target group.  
- **Result:** Visitors unknowingly download exploits.  
- **Defense:**  
  - 📶 **Web filtering** integrated with IAM  
  - 📡 **Browser isolation** for high-risk sites

---

## 👤 Impersonation & Pretexting
- **Method:** Posing as IT, HR, or a coworker to gain credentials.  
- **Result:** Victims willingly share passwords or tokens.  
- **Defense:**  
  - 🎓 **Regular awareness drills** (Domain 8)  
  - 🛡️ **Identity verification workflows** before sensitive actions

---

> 🔑 **Remember:**  
> Strong IAM processes (approval workflows, step-up MFA) can block attacks even when human error occurs.
