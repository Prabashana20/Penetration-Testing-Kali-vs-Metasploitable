# 🔒 Penetration Testing Project: Kali Linux vs. Metasploitable 2

This project simulates a full penetration test in a safe virtual lab using Kali Linux (attacker) and Metasploitable 2 (vulnerable target). It includes reconnaissance, vulnerability scanning, exploitation, and documentation.

---

## 🧰 Tools Used

- Kali Linux
- Metasploitable 2
- Nmap
- Nessus
- Metasploit Framework

---

## 🧪 Lab Environment

- VirtualBox VM setup
- Kali with Bridged + Host-Only network adapters
- Metasploitable with Host-Only adapter
- Isolated test network (`192.168.56.0/24`)

---

## 📊 Summary of Activities

| Phase                  | Tool        | Description                                              |
|------------------------|-------------|----------------------------------------------------------|
| Reconnaissance         | Nmap        | Identified live hosts and open ports                     |
| Vulnerability Scanning | Nessus      | Discovered critical vulnerabilities (e.g. CVE-2011-2523) |
| Exploitation           | Metasploit  | Gained remote shell access via vsftpd exploit            |

---

## 📁 Project Files

| File                            | Description                                   |
|---------------------------------|-----------------------------------------------|
| `Penetration_Test_Report.pdf`   | Full report with screenshots and results      |
| `nessus_report_vsftpd_scan.pdf` | Nessus scan showing vulnerable services       |
| `/screenshots/`                 | Visual evidence of scanning and exploitation  |
| `/nmap/nmap-scan.txt`           | Raw output from Nmap scans                    |
| `/metasploit/exploit_output.txt`| Terminal session of successful exploitation   |

---

## 📸 Screenshots

Screenshots are located in the `/screenshots/` folder and include:

- Nmap host and port scan
- Nessus vulnerability results
- Metasploit exploit session
- Post-exploitation commands

---

## 👨‍💻 Author

**Prabashana Kaveen**  
Email: prabashanapiris1234@gmail.com 


---

## ⚠️ Disclaimer

This project was executed in a fully isolated lab environment.  
**Do not attempt these techniques on real systems without proper authorization.**
