# Task-1-Nmap-Wireshark-local-network-scan-for-open-ports
Nmap + Wireshark local network scan for open ports
ip a
sudo nmap -sS 192.168.88.129/24 
sudo nmap -sS -sV 192.168.88.129/24 -oN nmap_scan.txt
sudo nmap -sS -sV -O 192.168.88.129/24 -oN scan_results.txt
PORT    STATE  SERVICE  VERSION                  RISK
53/tcp  open   domain   PowerDNS Recursor 4.8.8  Medium
