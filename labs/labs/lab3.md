# lab3 - Service detection

## Objectives
identify services running on open ports

## Command used
nmap -sV 192.168.0.1

## Explanation
- 'sV' detects service version
- helps identify outdated software that may contain vulnerabilities

## Example Output
PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 7.6
80/tcp   open  http    Apache 2.4.29

## Notes
Service detection helps security analysts identify potential vulnerabilities in outdated services.
