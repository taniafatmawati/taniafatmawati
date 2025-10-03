# Hi there, I'm Tania Fatma Wati 👋

[![Linkedin Badge](https://img.shields.io/badge/-taniafatmawati-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tania-fatma-wati/)](https://www.linkedin.com/in/tania-fatma-wati/)
[![Gmail Badge](https://img.shields.io/badge/-tania.fatmawati20@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:tania.fatmawati20@gmail.com)](mailto:tania.fatmawati20@gmail.com)

Welcome to my GitHub profile!  
I am a **Mathematics graduate** with a strong interest in **cybersecurity** and applied programming.  
This profile showcases my learning projects and academic showcases in **network security, cryptography, penetration testing, server hardening, and automation tools**.  

---

## 🔍 About Me
- 🎓 **Education**: Bachelor’s degree in Mathematics, Universitas Airlangga (June 2024, GPA: 3.71/4.00)  
- 🛡️ **Cybersecurity Projects**: Built and documented projects on VPN security, server hardening, AES file encryption, network packet analysis, and attack simulations.  
- 🌱 **Currently Learning**: Advanced penetration testing, secure file transfer, and cryptographic applications.  
- 💡 **Interests**: Network Security, Cryptography, Incident Response, Penetration Testing, and Security Hardening.  
- 📫 **Contact**: [LinkedIn](https://www.linkedin.com/in/tania-fatma-wati/) | [Email](mailto:tania.fatmawati20@gmail.com)  

---

## 🛠️ Skills & Tools

### 💻 Programming & Scripting
![Python Badge](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++ Badge](https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript Badge](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP Badge](https://img.shields.io/badge/-PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Dart Badge](https://img.shields.io/badge/-Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![SQL Badge](https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)


### 🔐 Cybersecurity & System Hardening
- **Network Security**: VPN (OpenVPN), Firewall Configuration (UFW, iptables)  
- **Penetration Testing**: Nmap, Hydra, hping3, attack simulation with Kali Linux  
- **Cryptography**: AES (ECB/CBC modes), PBKDF2 key derivation, DSA digital signatures  
- **Server Hardening**: Debian/Fedora setup, SSH key authentication, Nagios monitoring  
- **Incident Response**: Attack simulation, detection, and monitoring for brute-force & DoS  

---

## 📂 Featured Projects

Here are some of my academic and learning projects in cybersecurity, cryptography, and system hardening.

---

### [🔒 Secure File Transfer with AES-256 (CBC) + PBKDF2](https://github.com/taniafatmawati/secure-file-transfer-aes)  
**Sep 2025**  
Python tool for file encryption/decryption using AES-256 in CBC mode and PBKDF2-HMAC-SHA256 key derivation. Demonstrates applied cryptography and secure key derivation best practices.

**Key features**
- AES-256 (CBC) with PKCS7 padding, random IV and salt per file.
- Key derived from password using PBKDF2-HMAC-SHA256.
- Secure output format: `salt || iv || ciphertext`.
- CLI: `encrypt.py` / `decrypt.py` with example flows and demo files.

📄 [Repository & Documentation](https://github.com/taniafatmawati/secure-file-transfer-aes)

---

### [📡 Network Packet Analyzer (Mini Wireshark Clone)](https://github.com/taniafatmawati/network-packet-analyzer)  
**Jun 2025 – Aug 2025**  
A lightweight packet capture and analyzer built with Scapy (cross-platform). Shows TCP/UDP/ICMP classification, saves `.pcap`, and includes simple anomaly detection (suspicious port, DoS/port-scan heuristics).

**Key features**
- Live capture with friendly interface listing (psutil).
- Saves captures to `capture.pcap` (Wireshark compatible).
- Demo script for safe loopback testing and reproducible outputs.

📄 [Repository & Documentation](https://github.com/taniafatmawati/network-packet-analyzer)

---

### [⚡ API Stress Test (Lightweight Node.js Tool)](https://github.com/taniafatmawati/api-stress-tester)  
**Nov 2024 – Jan 2025**  
A small, easy-to-read Node.js stress tester for REST APIs, intended for academic demonstration. Useful for measuring throughput (TPS), latency, and error rate under configurable workloads and exporting results to CSV.

**Key features**
- Generic REST support (config via `.env`), concurrency-based scenarios.
- Computes throughput (TPS), average & max latency, and error rate.
- Exports reproducible results to `results.csv` for analysis.
- Minimal dependencies (`axios`, `dotenv`) and clear, commented code for teaching.

📄 [Repository & Documentation](https://github.com/taniafatmawati/api-stress-tester)

---

### [🚀 Cyber Attack Simulation for Penetration Testing (Kali Linux)](https://github.com/taniafatmawati/cyber-attack-simulation-penetration-testing)  
**Aug 2024 - Oct 2024**  
Educational Kali-based simulations for learning penetration testing: ping sweep, TCP port scans, SSH brute-force simulation, and controlled DoS simulations (lab only).

**Notes & safety**
- Lab-only, requires explicit permission to run against any non-owned systems.
- Includes logging, modular attack scripts, and safety flags (`--confirm`) to avoid accidental misuse.

📄 [Repository & Documentation](https://github.com/taniafatmawati/cyber-attack-simulation-penetration-testing)

---

### [🌐 Securing Fedora Server with OpenVPN: SSL/TLS Integration and Firewall Hardening](https://github.com/taniafatmawati/vpn-secure-implementation-fedora-server)  
**Aug 2024 – Sep 2024**  
Secure data communication through the configuration of a Virtual Private Network (VPN) using OpenVPN on a Fedora Server with SSL/TLS and advanced firewall hardening.

**Key results**
- Achieved end-to-end encryption of VPN traffic using SSL/TLS certificates.
- Applied firewall rules that reduced unauthorized access attempts by **~98%**.
- Full documentation including server/client configs, firewall rules, and verification captures.

📄 [Repository & Documentation](https://github.com/taniafatmawati/vpn-secure-implementation-fedora-server)

---

### [🖥️ Debian Server Setup & Hardening with Nagios Monitoring and Penetration Testing](https://github.com/taniafatmawati/debian-server-setup-and-hardening)  
**Jul 2024 – Aug 2024**  
Debian server hardening: SSH key authentication, UFW firewall policy, Nagios monitoring, and Kali-based penetration testing (Hydra, Nmap, hping3).

**Key results**
- Achieved complete reduction in successful brute-force logins after switching to SSH key auth.
- Reduced unauthorized access attempts by **~85%** through robust firewall configuration.
- Improved alerting and detection capabilities by enhancing Nagios configuration, resulting in a **~50%** increase in detected alerts.

📄 [Repository & Documentation](https://github.com/taniafatmawati/debian-server-setup-and-hardening)

---

### [📝 DSA with MD5 for Digital Signatures](https://github.com/taniafatmawati/dsa-md5-digital-signature)  
**Dec 2023 – Jan 2024**  
Educational implementation of DSA signatures combined with MD5 hashing to demonstrate signing & verification flows (note: MD5 used here for teaching; not recommended for production).

**Key results**
- Demonstrated key generation, signing, and verification.
- Streamlit demo app available for interactive exploration.

📄 [Repository & Documentation](https://github.com/taniafatmawati/dsa-md5-digital-signature)  
🔗 [Live demo (Streamlit)](https://taniafatma-digital-signature-app.streamlit.app/)

---

### [🛡️ AES Implementation for Text Data (C++)](https://github.com/taniafatmawati/aes-text-encryption-cpp)  
**Oct 2023 – Nov 2023**  
C++ implementation of AES-128 for text encryption (ECB demo), including SubBytes / ShiftRows / MixColumns / AddRoundKey, with parallelism for block processing.

**Key results**
- Functional AES-128 implementation with modular design (`aes.hpp`, `aes.cpp`, `main.cpp`).
- Achieved ~30% speed improvement using parallel block processing (demo measurements).

📄 [Repository & Documentation](https://github.com/taniafatmawati/aes-text-encryption-cpp)

---

## 📚 Certifications & Trainings

- **Endpoint Detection and Response (EDR) Certified Specialist** — Qualys Inc. (22 Sep 2024)  
- **Cloud Agent Certified Specialist** — Qualys Inc. (21 Sep 2024)  
- **CyberSecurity Asset Management (CSAM) Certified Specialist** — Qualys Inc. (16 Sep 2024)  
- **Vulnerability Management Detection and Response (VMDR) Certified Specialist** — Qualys Inc. (15 Sep 2024)  
- **Google Cybersecurity Professional Certificate** — Coursera / Google Career Certificates (10 Aug 2024)  
- **TensorFlow: Data and Deployment Specialization** — Coursera (23 Nov 2023)  
- **DeepLearning.AI TensorFlow Developer Professional Certificate** — Coursera (05 Nov 2023)  
- **Machine Learning Specialization** — Coursera (14 Oct 2023)  
- **Mathematics for Machine Learning and Data Science Specialization** — Coursera (24 Sep 2023)  
- **Leadership Workshop: Enhance Your Leadership Skills** — BCA (10 Jul 2023)  
- **Training: Financial Planning and Investment** — BCA (11 Apr 2023)  
- **Google IT Support Professional Certificate** — Coursera / Google Career Certificates (25 Dec 2022)  
- **Fresh Graduate Academy (FGA) — Frontend Developer (HTML, CSS & JavaScript)** — Digital Talent / Progate (29 Mar 2022)

---

## 🌐 Connect with Me
Feel free to connect via [LinkedIn](https://www.linkedin.com/in/tania-fatma-wati/) or [Email](mailto:tania.fatmawati20@gmail.com).  
I’m always open for discussions on cybersecurity, collaborative projects, or academic research.  

---
