# Task-1-Scan-Your-Local-Network-for-Open-Ports

Nmap scanning process on linux:
1. Open Terminal
2. Install nmap (sudo apt install nmap)
3. find your IP address (ifconfig or ip a)
4. Run a TCP SYN scan (nmap -sS mention IP address): Scan will show all the devices on ypur network. SYN scan is considered a "stealthy" scanning technique.
5. save the results (optional step): nmap -oN filename.txt IP address

   Steps i performed:
   1. Ctrl+Alt+T
   2. sudo apt install nmap
   3. ip a
   4. nmap -sS 92.168.29.110/24
   5. nmap -oN my_results.txt 192.168.29.110/24
