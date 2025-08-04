# nmap-task1
Learn to discover open ports on devices in your local network to understand network exposure.
"Install Nmap on Windows"
1.Go to https://nmap.org/download.html
2.Download the “Microsoft Windows Installer” version.
3.Run the .exe file and install Nmap (includes Zenmap GUI). 
# Syntax
nmap -sS {ip-addrs}
# Example Command 
nmap -sS 192.168.29.000
"Research: Common Services on Detected Ports & Security Risks"
--------------------------------------------------------------------------
| Port | Service | Risk Level | Description                              |
| ---- | ------- | ---------- | ---------------------------------------- |
| 22   | SSH     | Medium     | Used for remote login, should be secured |
| 80   | HTTP    | Low        | Web server                               |
| 139  | NetBIOS | Medium     | Used for file sharing, risky if public   |
| 445  | SMB     | High       | Vulnerable to malware (e.g., WannaCry)   |
| 3306 | MySQL   | High       | Database, risky if open to the internet  |
| 3389 | RDP     | High       | Remote Desktop, often brute-forced       |
--------------------------------------------------------------------------
