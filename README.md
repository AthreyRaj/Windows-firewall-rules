# 🔥 Task 4-3: Windows Firewall Configuration

## 🛡️ Objective
To configure a basic firewall rule on Windows using Windows Defender Firewall and understand how it filters inbound traffic.

---

## 🧰 Tools Used
- Windows Defender Firewall (Advanced Security)
- Windows 10

---

## 📝 Steps Performed

1. Opened **Windows Defender Firewall with Advanced Security** via Control Panel.
2. Navigated to **Inbound Rules** and created a new rule.
3. Chose:
   - **Rule Type:** Port  
   - **Protocol:** TCP  
   - **Port Number:** 23  
   - **Action:** Block the connection  
   - Applied to all profiles (Domain, Private, Public).
4. Named and saved the rule (`Block Port 23`).
5. Verified the rule was listed in Inbound Rules.
6. Disabled the rule afterward to restore the original state.

---

## 📸 Screenshots
All relevant screenshots are included in the `/screenshots/` folder:
- Rule creation wizard
- Firewall rule visible in the Inbound Rules list

---

## 🧠 What I Learned
- How to use Windows Firewall to block specific ports
- The difference between inbound and outbound rules
- Importance of blocking unused or vulnerable ports
- Managing and disabling rules safely

---

## ✅ Outcome
Successfully created, applied, and removed a custom inbound firewall rule on Windows. This task improved my understanding of network security through basic firewall rule management.

