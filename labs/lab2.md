# Lab 2 - Port Scanning with Nmap

## Objective
Scan a host to find open ports and the services running on them.

## Command Used
nmap -sS 192.168.1.10

## Explanation
- `-sS` performs a SYN scan (stealth scan)  
- Detects which ports are **open, closed, or filtered**  
- Helps identify services that may be vulnerable

## Sample Output
### PORT STATE SERVICE
- 22/tcp open ssh
- 80/tcp open http
- 443/tcp open https


## Notes
- Port scanning is **essential before deeper vulnerability testing**  
- Only scan networks you **own or have permission** to test
