# AT-Task1
# 🛡️ Task 1 - Reconnaissance & Scanning

**🎓 Internship:** Alfido Tech Cybersecurity Internship  
**👩‍💻 Intern:** Virendra Kumar  
**🗓️ Task:** Network Reconnaissance and Scanning using Netdiscover and Nmap

---

## 📝 Objective

The objective of this task is to perform **network reconnaissance** on a local network to:

- Identify **live hosts** using ARP-based discovery  
- Scan selected target for **open ports, services, and OS detection**  
- Understand basic scanning techniques using **Netdiscover** and **Nmap**

---

## 🧰 Tools Used

| Tool        | Purpose                                          |
|-------------|--------------------------------------------------|
| `Netdiscover` | Discovering live hosts on the local network     |
| `Nmap`        | Port scanning, service/version detection, and OS fingerprinting |

---

## 🔍 My Network Info

- **Local IP:** `192.168.154.xxx`  
- **Network Range:** `192.168.154.0/24`  
- **Target IP Selected:** `192.168.xxx.xx` (replace with actual IP)

---

## 🔹 Step-by-Step Summary

### 1️⃣ Discovering Devices on the Network

Command used:
```bash
sudo netdiscover -r 192.168.154.0/24
