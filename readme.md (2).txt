# Basic Network Scanning & Enumeration using Nmap

## Project Overview

This project demonstrates **basic network scanning and service enumeration** using **Nmap** in a **controlled lab environment**. The goal is to identify open ports and running services on a vulnerable test machine and understand how reconnaissance supports cyber security assessments.

> ⚠️ All scans were performed **only on local lab machines** created for learning purposes.

---

## Lab Setup

* **Attacker Machine:** Kali Linux
* **Target Machine:** Metasploitable 2
* **Virtualization:** VirtualBox (same NAT Network)

Both machines are isolated within a private network to ensure safe and legal testing.

---

## Tools Used

* **Nmap** – Network scanning and enumeration
* **Kali Linux** – Security testing OS
* **VirtualBox** – Virtual lab environment

---

## Scans Performed

The following Nmap scans were used during the project:

```bash
# Basic port scan
nmap <target-ip>

# Service and version detection
nmap -sV <target-ip>

# Aggressive scan (OS detection, versions, scripts)
nmap -A <target-ip>
```

---

## Key Findings

* Multiple **open ports** were identified (e.g., FTP, SSH, HTTP).
* **Service versions** revealed outdated or misconfigured services.
* The results highlight how exposed services can increase security risk if not properly secured.

---

## Learning Outcomes

* Understanding the role of **network reconnaissance** in cyber security
* Gaining hands-on experience with **Nmap scanning techniques**
* Interpreting scan results to identify **potential security risks**
* Building a safe and repeatable **virtual lab** for practice

---



**Demo Video:**

* LinkedIn: https://www.linkedin.com/posts/amal-n-k-032255364_cybersecurity-nmap-networksecurity-activity-7423678504153837568-mfq0?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFpzDuYBobGpFzcFAwUt0hxKGZ3Bx7RDj08

---

## Conclusion

This project provided practical exposure to basic network scanning and enumeration. Nmap is a powerful tool for identifying network exposure and is a foundational skill for anyone learning cyber security and ethical hacking.

---

## Disclaimer

This project is strictly for **educational purposes**. No real-world systems or public networks were scanned.
