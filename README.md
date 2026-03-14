# Abusing-DACL

# 🔴 Red Teaming – Active Directory Attack Techniques

![RedTeam](https://img.shields.io/badge/RedTeam-ActiveDirectory_Attacks-darkred?style=for-the-badge)
![MITRE](https://img.shields.io/badge/MITRE-ATT&CK-orange?style=for-the-badge)
![Windows](https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge)
![Pentesting](https://img.shields.io/badge/Pentesting-Privilege_Escalation-green?style=for-the-badge)

📚 This repository contains **Active Directory Red Teaming techniques** documented on **HackingArticles**.

These techniques demonstrate **privilege escalation paths caused by Active Directory misconfigurations**.

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

# 🛠️ Red Team Tools

| Tool | Description | OS |
|---|---|---|
| 🩸 BloodHound | Active Directory attack path discovery | Windows/Linux |
| 🔍 PowerView | AD enumeration framework | Windows |
| ⚔️ Impacket | Python exploitation toolkit | Linux |
| 🧬 BloodyAD | Active Directory abuse automation | Linux |
| 🔑 Mimikatz | Credential extraction tool | Windows |
| 💻 Evil-WinRM | Remote PowerShell shell | Linux |

---

# 🔍 Enumeration Example

```bash
bloodhound-python -u user -p password -d domain.local -c All
