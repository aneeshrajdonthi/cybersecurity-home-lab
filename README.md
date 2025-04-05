# cybersecurity-home-lab
Personal cybersecurity lab setup with VirtualBox, Kali Linux, and vulnerable machines for ethical hacking practice.
# 🛡️ Cybersecurity Home Lab

This repository documents my personal cybersecurity home lab built for ethical hacking, penetration testing, and red-team training using VirtualBox and open-source tools.

---

## 🎯 Objective

To simulate real-world offensive and defensive security scenarios in an isolated environment using Kali Linux, vulnerable VMs, and a custom network topology.

---

## 💻 Host Environment

- **Host OS**: Windows 11
- **Virtualization**: VirtualBox 7.x
- **Memory**: 8 GB
- **VMs**: Kali Linux (Attacker), Metasploitable2 (Target)

---

## 🌐 Network Configuration

| Adapter | Interface | Type        | IP Address       | Purpose           |
|---------|-----------|-------------|------------------|-------------------|
| 1       | `eth0`    | Bridged     | 192.168.29.206   | Internet Access   |
| 2       | `eth1`    | Host-Only   | 192.168.56.101   | Internal Lab Net  |

---

## 🛠️ Tools Used

- 🔹 Kali Linux
- 🔹 Metasploitable 2
- 🔹 Nmap
- 🔹 Wireshark
- 🔹 Metasploit
- 🔹 Burp Suite (Planned)

---

## 📸 Screenshots

| Command         | Output Example                |
|------------------|-------------------------------|
| `ip a`           | ![](screenshots/ip-a-output.png) |
| `ip route show`  | ![](screenshots/ip-route.png)   |

---

## 🧪 Lab Activities

### ✅ Initial Setup
- [x] Installed Kali Linux and Metasploitable
- [x] Configured Bridged + Host-only adapters
- [x] Verified IP addresses and routing

### 🔍 Recon & Scanning
- [ ] Full Nmap scan of Metasploitable
- [ ] Port analysis (FTP, Telnet, SMB, etc.)

### ⚔️ Exploitation (Planned)
- [ ] FTP backdoor exploit (vsftpd)
- [ ] Weak SSH credentials
- [ ] Manual HTTP vuln exploitation

---

## 📈 To-Do / Roadmap

- [ ] Document Nmap scans
- [ ] Automate common recon tasks
- [ ] Start defensive side with Suricata + ELK
- [ ] Document learning in blog posts

---

## 🧠 Author

**Aneesh Raj**  
Cybersecurity Enthusiast | Mechanical Engineer turned Ethical Hacker  
[LinkedIn](#) • [GitHub](https://github.com/aneeshraj)

---

> **Disclaimer**: This lab is entirely offline and used strictly for legal cybersecurity training and personal development.

