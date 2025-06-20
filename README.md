# 🔓 Real-World Attack Simulation Lab

This repository documents several offensive security attacks I performed in a **controlled lab environment** using Kali Linux, vulnerable machines, and real Wi-Fi hardware. These attacks were part of my independent cybersecurity learning following HackerU's ethical hacking curriculum.

Each attack includes:

- 🎯 Objectives
- 🛠️ Tools used
- 🧪 Step-by-step commands
- 📸 Screenshots
- ✅ Results

---

## 📁 Included Attacks

### 🧠 1. [EternalBlue Exploit (MS17-010) + Screenshot via Meterpreter](attacks/eternalblue-metasploit/)
- Used Metasploit to scan and exploit a Windows 7 machine vulnerable to EternalBlue.
- Gained a reverse Meterpreter shell.
- Took a screenshot from the victim machine as proof of access.

### 📡 2. [Evil Twin Wi-Fi Attack using Airgeddon + Alfa Adapter](attacks/evil-twin-airgeddon/)
- Created a rogue access point with the same SSID as a real Wi-Fi network.
- Deauthenticated users from the real AP.
- Captured WPA handshake and credentials using a phishing portal.

### 🔄 3. [MITM Attack (ARP Spoofing + HTTP Credential Sniffing)](attacks/mitm-arp-http-sniffing/) 
- Manually enabled IP forwarding.
- Used `arpspoof` and `tcpdump`/`wireshark` to capture credentials from HTTP login pages.

---

## ⚠️ Legal Disclaimer

All attacks shown here were performed on systems I own or had explicit permission to test.  
They are shared for **educational and demonstration purposes only**.  
**Do not** attempt any of these attacks on unauthorized systems or networks.

---

## 📌 About

These labs reflect my practical experience in:
- Network attacks (MITM, DoS)
- Exploiting known CVEs (EternalBlue)
- Wi-Fi hacking (Evil Twin, EAPOL capture)
- Post-exploitation with Metasploit

> 🛠 Tools used: Kali Linux, Metasploit, Airgeddon, Alfa AWUS036ACH, Airodump-ng, Arpspoof

