# Networking-labs & Projects
Collection of my networking projects and lab experiments (CCNA, Python automation, cloud networking)

Hi, I'm Saravana Kumar
Aspiring **Junior Network Engineer** with hands-on experience in networking labs, Python automation, and cloud networking.

## 🔑 Skills
- CCNA-level Networking (Routing, Switching, OSPF, VLANs, ACLs)
- Network Automation (Python, Netmiko, Paramiko)
- Cloud Networking (AWS VPC, Azure VNets)
- Tools: Cisco Packet Tracer, GNS3, Wireshark

- ## 📂 Projects & Labs

### 🔹 CCNA Labs
- **Lab 1: Configured and verified DNS, HTTP, and FTP services in Packet Tracer
- **Lab 2: Configured static routing and OSPF between two routers in Packet Tracer to enable inter-LAN connectivity.
- **Lab 3: Configured VLANs and inter-VLAN routing (Routing-on-a-Stick) to enable communication between multiple VLANs.


- **Lab 1: Network Services (DNS, HTTP, FTP)

What the lab does:
Demonstrates configuring a server with DNS, HTTP, and FTP services in Packet Tracer.
Shows how a PC can access a website via hostname using DNS resolution.
Tests file transfer between PC and server using FTP.

Devices used:
1 Server
1 PC
(Optional: Switch for network connectivity if needed)

Objectives:
Configure DNS records and enable HTTP service.
Access web pages via hostname.
Enable and test FTP file transfer.

Steps to run the lab:
Add a server and configure IP: 192.168.1.100/24, Gateway 192.168.1.1.
On Server → Services:
Enable DNS and add record: web → 192.168.1.100
Enable HTTP and optionally edit index.html
Enable FTP
On PC: set DNS to 192.168.1.100.
Open browser → go to http://web to verify HTTP.
Test FTP using PC File Transfer app.

Verify:
Server: running configuration (GUI)
PC: nslookup web
