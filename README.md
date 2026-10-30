### Hi, I'm Eddy 👋

Aspiring network engineer based in Calgary, CCNA certified, currently job hunting for NOC Technician and Junior Network Administrator roles (MSP, energy, telecom).

**Main project:** [`hybrid-physical-virtual-lab`](https://github.com/edmund-igweonu/hybrid-physical-virtual-lab) is my ongoing hands-on lab, combining physical gear (two Cisco 881 routers, a Cisco Catalyst 2950 and a TP-Link SG105E) with GNS3, Docker and Packet Tracer. It's a growing collection of 18 labs rather than a single project, each with configs, screenshots and a writeup of what broke along the way. Some highlights:

- **Physical router redundancy:** HSRP on the two 881s with a real cable-pull failover measured from a client, then IP SLA tracking so the router steps down when its upstream dies even though the link stays up
- **Flagship build:** a two-site (HQ + Branch) multi-VLAN enterprise network with real switching hardware bridged into a GNS3 virtual OSPF routing setup
- **Routing:** eBGP across three AS's, EIGRP/OSPF/BGP redistribution, and an MPLS L3VPN with overlapping customer subnets in separate VRFs
- **Security:** a three-legged firewall/NAT with a DMZ, site-to-site GRE-over-IPsec VPN, TACACS+ AAA, 802.1X with FreeRADIUS, and DHCP snooping and port security
- **Switching:** LACP vs. static EtherChannel and PVST+ root election, both with failover testing
- **Automation and monitoring:** Netmiko config backups, centralized syslog in Loki and Grafana, and synthetic WAN monitoring

Other repos on my profile are earlier or more focused builds: Packet Tracer topologies, an Active Directory lab, and Calgary-specific WAN/enterprise network designs.

📫 Open to networking roles in Calgary. Feel free to reach out.
