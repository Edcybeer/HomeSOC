# HomeSOC

# Overview
This lab simulates a realistic enterprise network using pfSense as the firewall/router. It includes offensive, defensive, and monitoring tools to practice penetration testing, Active Directory attacks, and SIEM logging.

# Tools/OS Installed
- VirtualBox
- Kali Linux
- Windows 11
- Windows Server (Active Directory)
- Metasploit Framework
- pfSense (Firewall/Router)
- Splunk (SIEM)

---

# Network Topology

Diagram Overview:

pfSense Firewall

IP: 192.168.1.10

DHCP: 192.168.1.20 – 192.168.1.50

Kali Linux

IP: 192.168.1.100

Purpose: Offensive testing, exploitation

Windows 11

IP: 192.168.1.101

Target system for attacks

Metasploit VM

IP: 192.168.1.7

Exploit framework testing

Windows Server

Role: Active Directory Domain Controller

Services: AD DS, DNS, GPO

Splunk SIEM

Purpose: Log collection, detection, and response



---

# Tasks Completed
Installed and configured pfSense (LAN/WAN, DHCP, firewall rules)

Deployed Windows Server, installed Active Directory Domain Services (AD DS)

Created domain lab.local, added users and GPOs

Installed Kali Linux and Metasploit for offensive testing

Set up Splunk, forwarded logs from Windows and pfSense

Simulated attacks, analyzed logs and alerts in Splunk

