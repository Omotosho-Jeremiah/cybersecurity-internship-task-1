# Cybersecurity Internship - Task 1: Network Port Scanning  

📌 Task Objective  
I Performed a network port scan using Nmap to identify open ports and assess security risks.  

🔍 Tools Used  
- Nmap: For port scanning (`nmap -sS 192.168.1.0/24`).    

📂 Files Included  
1. `scan_results.txt`: Raw Nmap scan output.  
2. `scan_screenshot.png` : Proof of scan execution.  

🚀 Steps Performed  
1. Identified local IP range (`192.168.1.0/24`).  
2. Ran TCP SYN scan:  
   ```bash
   nmap -sS 192.168.1.0/24 -oN scan_results.txt
