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

VLAN Interface Configuration
VLAN	Interface IP (pfSense)	DHCP Range	DNS Server
VLAN10	192.168.10.1/24	192.168.10.20 – 192.168.10.50	192.168.10.1 (local DNS)
VLAN20	192.168.20.1/24	192.168.20.20 – 192.168.20.50	192.168.20.1
VLAN30	192.168.30.1/24	192.168.30.20 – 192.168.30.50	192.168.30.1
VLAN40	192.168.40.1/24	192.168.40.20 – 192.168.40.50	192.168.40.1

---

# Tasks Completed
Installed and configured pfSense (LAN/WAN, DHCP, firewall rules)

Deployed Windows Server, installed Active Directory Domain Services (AD DS)

Created domain lab.local, added users and GPOs

Installed Kali Linux and Metasploit for offensive testing

Set up Splunk, forwarded logs from Windows and pfSense

Simulated attacks, analyzed logs and alerts in Splunk

