# Assessing-Network-with-Wireshark-and-Zenmap
This project is a detailed account of my first steps into the wild world of network analysis. Using Wireshark to snoop on data packets and Zenmap to discover what's hiding on the network, I've got a lot to show. It turns out, network traffic is way more exciting than watching paint dry (maybe). Seriously. All the lab deliverables are below.

## Cybersecurity and Network Analysis Tools: ##

- Wireshark: A tool to capture and analyze network traffic.
- Zenmap: The graphical interface for Nmap, used to map networks and find open ports.
- Nmap: A command-line tool for network discovery and security scanning.
- TCPDUMP: A command-line packet analyzer for Linux.

## Command-Line Utilities: ##

- ipconfig: Displays network configuration on Windows.
- ifconfig: Displays network configuration on Linux.
- ARP: A protocol to find a device's MAC address from its IP address.
- Ping: Tests the connectivity of a host.
- Hping3: Generates and analyzing TCP/IP packets.



## Topology: ##
<img width="567" height="310" alt="Screenshot 2025-08-27 at 11 56 22 AM" src="https://github.com/user-attachments/assets/53969f45-dd30-4309-8839-c348992415f8" />

- vWorkstation (Windows Server 2019)

- TargetWindow01 (Windows Server 2019)

- TargetLinux01 (Ubuntu Linux)

- AttaxkLinux01 (Kali Linux)

- RemoteWindows01 (Window Server 2019)

## Sections: ##

**Section 1**: Hands-On Demonstration:

This section provided a step-by-step walkthrough for performing network reconnaissance on a Local Area Network (LAN). Key tasks included:

- Using ipconfig, arp, and ping to explore the LAN and populate a network assessment spreadsheet.
- Capturing and analyzing network traffic using Wireshark and Zenmap to understand the behavior of ICMP and ARP packets during various scans (Ping, Regular, and Intense).

**Section 2** Applied Learning:

This section required applying the skills from Section 1 to a Wide Area Network (WAN) with less direct guidance. The focus was on using more command-line-based tools:

- Exploring the WAN from an AttackLinux machine using ifconfig and arp.
- Capturing and analyzing traffic with hping3 and tcpdump, including observing the three-way handshake process and performing "banner grabbing" to identify services.

