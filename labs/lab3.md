# Lab 3 - Service Detection

## Objective
Identify services and versions running on open ports.

## Command Used
nmap -sV 192.168.1.10

## Explanation
- `-sV` detects service versions
- Helps identify outdated software that may contain vulnerabilities

## Example Output
PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 7.6
80/tcp   open  http    Apache 2.4.29

## Notes
Service detection helps security analysts identify potential vulnerabilities in outdated services.
