# Information_Gathering_on_Websites_Using_Linux
This project demonstrates practical use of Linux tools for reconnaissance and network analysis as part of an ethical hacking and cybersecurity workflow. It includes four labs covering information gathering techniques such as scanning, MAC spoofing, port analysis, and packet inspection.

🧪 Lab Overview
🔍 Lab 1: Nmap – Network Scanning
Identified IP address of the target Windows machine.

Scanned the machine to retrieve:

OS details using nmap -O

Port details using nmap -p-

Service versions using nmap -sV

🔄 Lab 2: Macchanger – MAC Address Spoofing
Used macchanger -r eth0 to assign a random MAC address.

Demonstrated how MAC addresses can be anonymized for penetration testing.

🔢 Lab 3: Netstat – Network Statistics
Used netstat -a to list all open connections and listening ports.

Used netstat -r to display the system's routing table.

Utilized --help to understand netstat options and syntax.

🧷 Lab 4: Wireshark – Packet Analysis
Analyzed captured network traffic using rogue_user.pcap.

Identified key protocols (TCP, UDP, ARP) via Protocol Hierarchy.

Used tcp.stream filters to track and extract actual data passed over TCP connections.

Created custom columns in Wireshark for TCP stream identification.

🛠️ Tools & Commands Used
nmap, macchanger, netstat, Wireshark

Linux Terminal, Display Filters, and Stream Analysis in Wireshark

🎯 Purpose
To build hands-on expertise in information gathering using open-source tools. This foundational knowledge is vital for tasks such as vulnerability assessments, penetration testing, and ethical hacking.
