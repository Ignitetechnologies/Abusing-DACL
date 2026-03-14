# Abusing-DACL

## 🌐 Connect With Us

🔵 **[Telegram – Join Channel](https://t.me/hackinarticles)**  
⚫ **[Twitter/X – Follow Us](https://x.com/hackinarticles)**  
🟣 **[Discord – Join Server](https://discord.com/invite/kyKvXwK4Bk)**  
💼 **[LinkedIn – Follow HackingArticles](https://www.linkedin.com/company/hackingarticles)**  

## 🎓 Training Program

🚀 **[Join Our Cybersecurity Training Program](https://forms.gle/bowpX9TGEs41GDG99)**  

Hands-on training in **Penetration Testing, Red Teaming, and Cybersecurity.**

---

# 📑 AD-DACL Abuse Techniques

| # | Attack Technique | Category | Difficulty | Article |
|---|---|---|---|---|
| 1️⃣ | **WriteDACL** | Permission Abuse | 🟡 Medium | https://www.hackingarticles.in/abusing-ad-dacl-writedacl |
| 2️⃣ | **WriteOwner** | Privilege Escalation | 🟡 Medium | https://www.hackingarticles.in/abusing-ad-dacl-writeowner |
| 3️⃣ | **GenericWrite** | Attribute Manipulation | 🟡 Medium | https://www.hackingarticles.in/genericwrite-active-directory-abuse |
| 4️⃣ | **GenericAll** | Full Object Control | 🔴 High | https://www.hackingarticles.in/genericall-active-directory-abuse |
| 5️⃣ | **AddSelf** | Group Privilege Abuse | 🟢 Easy | https://www.hackingarticles.in/addself-active-directory-abuse |
| 6️⃣ | **AllExtendedRights** | Advanced Privilege Abuse | 🔴 High | https://www.hackingarticles.in/allextendedrights-active-directory-abuse |
| 7️⃣ | **ForceChangePassword** | Password Manipulation | 🟢 Easy | https://www.hackingarticles.in/forcechangepassword-active-directory-abuse |

---

# 🧠 Attack Impact

| Permission | Impact | Risk |
|---|---|---|
| GenericAll | Full control over object | 🔴 Critical |
| GenericWrite | Modify object attributes | 🟠 High |
| WriteOwner | Change object ownership | 🟠 High |
| WriteDACL | Modify object permissions | 🔴 Critical |
| AddSelf | Add attacker to privileged group | 🟠 High |
| AllExtendedRights | Perform DCSync attack | 🔴 Critical |
| ForceChangePassword | Reset account password | 🟡 Medium |

---

