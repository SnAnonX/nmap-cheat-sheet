# Nmap Cheat Sheet

Basic Nmap commands for beginners to start network scanning and security testing.

---

## Basic Nmap Commands:

- `nmap -sS 192.168.1.1` → TCP SYN scan  
- `nmap -A 192.168.1.1` → Aggressive scan  
- `nmap -p- 192.168.1.1` → Scan all ports  
- `nmap -sV 192.168.1.1` → Service/version detection  
- `nmap --script vuln 192.168.1.1` → Vulnerability scan  
- `nmap -O 192.168.1.1` → OS detection

---

## How to Use This Nmap Cheat Sheet

This cheat sheet contains basic and useful Nmap commands for beginners to get started with network scanning and security testing.

**To use these commands:**

1. **Open your terminal or command prompt** on your computer (Linux, Windows, or Mac).  
2. **Make sure Nmap is installed.**  
   - On Linux: use `sudo apt install nmap` (Debian/Ubuntu) or equivalent.  
   - On Windows/Mac: download from [nmap.org](https://nmap.org).  
3. **Run the commands as shown in this cheat sheet**, replacing the example IP address (`192.168.1.1`) with the target IP or domain you want to scan.

   Example:  
   ```bash
   nmap -sS 192.168.1.1
