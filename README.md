# hostscan

A bash script for performing port scan, version detection and script scan on a single target using nmap.
Scan results will be produced in the current directory

if port 80 is detected, gobuster will be used to perform directory brute-force on the target.

```
Usage: hostscan [TARGET_IP]
```
