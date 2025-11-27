# 🔐 Man-in-the-Middle (MITM) Attack – Home Lab Analysis  
### ARP Spoofing | Ettercap | Bettercap | Defensive Detection

## 📌 Overview
This project demonstrates a **Man-in-the-Middle (MITM)** attack performed in an isolated VMware lab using my own devices.  
The goal of this project is to study:
- ARP spoofing/poisoning behavior  
- How MITM traffic appears in Wireshark  
- How tools like Ettercap and Bettercap operate  
- Defensive techniques to detect and prevent MITM attacks  

This is a **defensive cybersecurity learning project**, not malicious activity.



## 🛠️ Tools Used
- Kali Linux  
- Ettercap  
- Bettercap  
- arpspoof  
- Wireshark  
- VMware Workstation Lab Network  

---

## 🧪 Techniques Performed
### 1️⃣ ARP Spoofing / Poisoning  
- Observed ARP table changes  
- Captured ARP reply floods  
- Monitored traffic redirection  

### 2️⃣ Ettercap  
- Used for automated ARP spoofing  
- Captured network flows  
- Inspected host interactions  

### 3️⃣ Bettercap  
- Monitored real-time traffic  
- Visualized network topology  
- Logged MITM activity  

---

## 📡 Packet Analysis Summary
- Identified ARP reply packets sent without request  
- Observed MAC address substitution  
- Logged suspect ARP behavior patterns  
- Detected anomalies in traffic routing  

---

## 🛡️ Defensive Takeaways
- How to detect MITM using ARP inspection  
- How to use Wireshark filters (`arp.opcode == 2`)  
- Network segmentation importance  
- Enabling DHCP snooping / Dynamic ARP Inspection  
- Role of HTTPS in protection against MITM  

---

## 📄 Report
The full PDF report with screenshots and analysis is available here:  
**MITM Attack.pdf**

---

## ⚠️ Disclaimer  
This project was conducted strictly inside a **private, isolated home lab** using only my own devices for educational and defensive research. 
