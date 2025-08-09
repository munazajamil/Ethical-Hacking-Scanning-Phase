Nmap Scanning Practice:

🎯 Goal
Identify open ports and services on the target system.

🔹 Command Used:

"nmap -sS -A 192.168.1.10"
"nmap -A testphp.vulnweb.com"
"nmap -oS testphp.vulnweb.com"
"nmap -sS testphp.vulnweb.com"

-sS → SYN scan
-oS  → operatinf system detection scan
-A → Detect OS and service versions

For scan we can use url or IP Address

Summary of Results:
Open ports: 22 (SSH), 80 (HTTP)
OS: Ubuntu 20.04
Web server detected: Apache 2.4.41
