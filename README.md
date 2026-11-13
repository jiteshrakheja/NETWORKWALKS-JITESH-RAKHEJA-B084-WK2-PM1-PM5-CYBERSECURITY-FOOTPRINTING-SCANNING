# NETWORKWALKS-SATYAK-KUMAR-B084-WK2-PM1-PM5-CYBERSECURITY-FOOTPRINTING-SCANNING

## 📌 Project Overview

This repository contains my Week 2 project submission for the **Networkwalks Academy Cybersecurity \& Ethical Hacking Program (Batch B083C)**.

Two modules were completed:

* **W2-PM1** — Footprinting \& Reconnaissance with Multiple Kali Tools
* **W2-PM5** — Network Scanning with Zenmap

## 🎯 Objective

To perform passive reconnaissance against a live target domain using six Kali Linux tools, and to perform active host discovery on my own local network using Zenmap — then document both in a single professional penetration-testing report.

## 🛠️ Tools Used

|Tool|Purpose|
|-|-|
|whois|Domain registration lookup|
|whatweb|Web technology fingerprinting|
|nslookup|DNS resolution|
|curl -I|HTTP response header inspection|
|wafw00f|Web Application Firewall detection|
|dnsrecon|Full DNS record enumeration|
|Zenmap (Nmap GUI)|Local network host discovery \& topology mapping|
|Windows ipconfig|Local IP/subnet identification|

## 📂 Repository Structure

```
├── README.md
├── W2-PM-FINAL\_Report\_Ahmed.docx      # Final combined report
├── screenshots/
│   ├── W2-PM1/
│   │   ├── 01\_whois.png
│   │   ├── 02\_whatweb.png
│   │   ├── 03\_nslookup\_curl.png
│   │   ├── 04\_wafw00f.png
│   │   └── 05\_dnsrecon.png
│   └── W2-PM5/
│       ├── 01\_ipconfig.png
│       ├── 02\_zenmap\_pingscan.png
│       ├── 03\_topology.png
│       └── 04\_topology\_legend.png
├── outputs/
│   ├── whois.txt
│   ├── whatweb.txt
│   ├── nslookup.txt
│   ├── curl.txt
│   ├── wafw00f.txt
│   └── dnsrecon.txt
└── topology.pdf                        # Zenmap topology export
```

## 🔍 W2-PM1 — Footprinting Summary (Target: networkwalks.com)

|Task|Finding|
|-|-|
|whois|Registrar: GoDaddy.com, LLC — Name servers: HostGator|
|whatweb|WordPress 7.1.1, WP Download Manager 3.3.58, Server IP: 192.232.216.135|
|nslookup / curl -I|IP confirmed; WordPress security plugin visible in HTTP headers|
|wafw00f|Protected by ModSecurity (SpiderLabs)|
|dnsrecon|SOA, NS, A records + 8 SRV records (cPanel autodiscover)|

## 🖥️ W2-PM5 — Network Scanning Summary (My Local LAN)

|Task|Finding|
|-|-|
|Local IP / Subnet|192.168.1.100 / 192.168.1.0/24|
|Live hosts|2 (router `flybox.home` + my PC)|
|IP addresses|192.168.1.1, 192.168.1.100|
|MAC addresses|F0:55:01:45:59:BC (router — Huawei Device)|
|Topology|Saved as PDF (see `topology.pdf`)|

## 🧩 Troubleshooting Experience

<!-- Write one real problem you faced during this week's tasks and how you solved it. Example format below — replace with your own experience. -->

**Problem:** *\[describe an issue you ran into, e.g. Zenmap not detecting the correct subnet, or a scan returning fewer hosts than expected]*
**Solution:** *\[describe how you fixed or worked around it]*

## ⚠️ Disclaimer

All activities in this repository were performed only against systems I own or have explicit written permission to test (networkwalks.com is used here under the standing permission granted for this course's lab exercises; my own LAN is my own property). This work is for educational purposes only as part of the Networkwalks Academy Cybersecurity \& Ethical Hacking Program.

## 👤 Author

**Jitesh Rakheja**
Cybersecurity Trainee — Networkwalks Academy, Batch B084
GitHub: [@](https://github.com/satyak99108)jiteshrakheja



