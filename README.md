# Nmap Network Scan

This repository contains results and analysis of a basic network reconnaissance exercise using **Nmap** on a local network.

## 🔍 Objective
To discover open ports on devices in your local network to understand network 
exposure.  

## 🛠️ Tools Used
- [Nmap](https://nmap.org) - Network scanning and service detection
- [Kali Linux](https://www.kali.org) - Penetration testing OS

## 📋 Steps Performed
1. Installed Nmap on Kali Linux
2. Identified local IP range (`192.168.56.0/24`)
3. Ran TCP SYN scan
4. Noted open port
5. Ran service version detection
6. Researched the service and identified potential risks
7. Saved scan outputs as screenshots and text

## Security Risks Identified
MySQL (port 3306) is open and accessible
Risk of:
- Unauthorized access
- Unencrypted communication
- Brute-force attacks
- Data leakage

## Files Included
nmap_scan_result.txt - Nmap output

Elevate Labs Task 1.pdf - Detailed Documentation of the entire task

README.md - Brief Project documentation


   
